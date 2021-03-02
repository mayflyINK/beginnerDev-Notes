# Setting up a localhost

- make sure python is installed (this should be installed as part of node.js)
  - `py -v`

open bash
If Python version returned above is 3.X
- `python3 -m http.server`

On windows try "python" instead of "python3", or "py -3"
If Python version returned above is 2.X
- `python -m SimpleHTTPServer`

If not able to use default port 8000
- `python -m http.server 8001`
- http://localhost:8001

https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server
