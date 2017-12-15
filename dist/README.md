# Feed Reader Testing Project

## List of Tests
- RSS Feeds
    - URL is defined and it is not empty.
    - name is defined and it is not empty.
- The menu
    - menu element is hidden by default.
    - menu changes visibility.
- Initial Entries
    - there is at least one entry element.
- New Feed Selection
    - Feed content actually changes when a new element is added.

## Run the application
The ways to run the application are:
- Clone or Download the respository
    - Extract the zip file.
    - Open the index.html file in the extracted folder.
- Another way to run the application after downloading the respository is:
    - All you need is [Python]('https://www.python.org/downloads/') and a command line.
    - Open the terminal (Mac and Linux) or command prompt (Windows) in the folder containing the index.html file.
    - Run `python --version`. If Python is installed, you'll see "Python X.Y.Z". The "X" will be 2 or 3, indicating Python 2 or 3. If nothing shows up or the command produces an error, I recommend that you download Python.
    - If you have Python 2, `run python -m SimpleHTTPServer 8000`. If you have Python 3, run `python -m http.server 8000`.
    - Navigate your browser to http://localhost:8000/.

## Attributions
- [Jasmine]('https://jasmine.github.io/')
