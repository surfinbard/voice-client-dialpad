# Dialpad for Twilio browser calls, Revisited

## Introduction

I call places, and I often have to pick options from automated menus before talking to a human being. The original code for browser calls doesn't include an option to type mid call. This is the solution for that!

Big thanks to David Dooley, who posted the original dialpad on Twilio's blog.

## Prerequisites

	You've already installed the JS SDK quickstart application: 
      https://github.com/TwilioDevEd/voice-javascript-sdk-quickstart-node
	Your application is currently placing outgoing calls successfully

## How to use this

Pretty straightforward: 
	
	Navigate to /public (at the time of writing, directly under the root directory);
    Replace the triad (HTML, CSS and JS) with the files in this repository.
 
Mind the filenames: there's another JS file in /public we're not changing. I've left the original names so you know what's what. 
