# Lean_GoalTree
Get the crucial Goal Tree structure for Lean code. A static version of Paper-Proof.


Just put it in your project repository. Rename it to `goaltree.lean`. In your `lakefile.toml`, add:
```bash
[[lean_exe]]
name = "goaltree"
supportInterpreter = true

[[require]]
name = "metalib"
git = "https://github.com/reaslab/metalib.git"
rev = "main"
```
Then use
```bash
lake clean
lake exe goaltree LEAN_FILE_PATH CONSTANT_NAME OUTPUT_PATH
```
to run.

____________________________________________
We use(modify) codes of Paperproof by lakesare, codes of Animate-lean-proofs by dwrensha, and codes of Jixia by kokic.
