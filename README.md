# Lean_GoalTree
Get the crucial Goal Tree structure for Lean code. A static version of Paper-Proof.


Just put it in your project repository. In your `lakefile.toml`, add:
```bash
[[lean_exe]]
name = "goaltree"
supportInterpreter = true
```.

Then use
```bash
lake clean
lake exe goaltree LEAN_FILE_PATH CONSTANT_NAME OUTPUT_PATH
```
to run.
