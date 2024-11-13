- `nix flake init --template github:cachix/devenv`
- `direnv allow`

(⚠️ WILL OVERRIDE FILES WITH THE SAME NAME ⚠️)
```
cp -f <this_project_path>/.clang-format \
<this_project_path>/.clangd \
<this_project_path>/.gitignore \
<this_project_path>/.ignore \
<this_project_path>/flake.nix <unreal_project_path>
```

- update `flake.nix` (UPDATE_HERE)
