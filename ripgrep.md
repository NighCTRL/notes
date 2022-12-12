Search for text faster for grep
rg test ~/.local/state/
  -> Search 'test' in ~/.local/state/ folder
rg Test
  -> Search recursively the current working directory
rg --filtype html h1
  -> Search only html file
rg Hello --glob README.*
  -> search for 'hello' in all README files (.txt/.md/)
rg --files-with-matches Hello
  -> Ouput only the files matching a certain serch
rg --invert-match Hello
  -> Only return files not matching
