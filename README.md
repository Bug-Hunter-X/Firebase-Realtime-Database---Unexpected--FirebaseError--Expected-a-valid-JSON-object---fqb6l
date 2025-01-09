# Firebase Realtime Database - Unexpected 'FirebaseError: Expected a valid JSON object.'

This repository demonstrates a bug encountered when using the Firebase Realtime Database, where the error `FirebaseError: Expected a valid JSON object.` is thrown even when seemingly valid JSON is being written.  The issue seems to stem from subtle inconsistencies in data types or unexpected characters within the JSON data, leading to Firebase's JSON parser rejecting the data.

The `bug.js` file shows the code that produces the error.  `bugSolution.js` demonstrates a corrected version that addresses the issue.  See the detailed explanation in the respective files for further analysis.