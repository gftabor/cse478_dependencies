# cse478_dependencies

Holds references to the versions of MuSHR dependencies required for the Spring 2021 offering of CSE478. These references are in the form of Git submodules pointing at commits on as-yet unmerged branches of the official MuSHR code.

## Usage

To populate the submodule directories with the referenced versions of the code:
    
    git submodule update --init --recursive

<details>

<summary>Development</summary>

Each submodule is tracking a branch, so you can bump all submodules to the tip of their remote branches with:

    git submodule update --recursive --remote

The updated references can then be commited.

</details>
