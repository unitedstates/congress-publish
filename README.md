## Congress API Updater

A script to pull data from unitedstates Congress wiki and update a repository with the individual json files contained within.

### Usage

	./publish --congresses=113

#### The Process:

1. Download zip file to congress-data directory
2. Check for directory containing respository (congress-bills-[congress]); create and initialize if not
3. Switch to gh-pages branch or create if needed
4. Unzip contents of zip file into directory
5. git push origin gh-pages