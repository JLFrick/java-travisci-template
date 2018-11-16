[![Build Status](https://travis-ci.com/JLFrick/java-travisci-template.svg?branch=master)](https://travis-ci.com/JLFrick/java-travisci-template)
# Java TravisCi Template

It comes integrated with Travis CI, so continuous integration comes out of the box.

## First Steps
- Clone or download this repo
- Make a new Java Project in the java-travisci-template folder
- Create your own Java program in the src-folder and the specific JUnit-Test in the test-folder

## Next Steps
- Stage and commit the changes
- Activate and trigger a build on Travis

## Imports
- Import the below into your JUnit-Test
	import static org.junit.Assert.*;
	import org.junit.Test;
## How to link your build status
- Go to Travis & chose your repo
- Click on the "build passing" button
- Change the "Image URL" to "Markdown"
- Copy and Paste the link into your Readme-file
