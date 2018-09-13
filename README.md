Parcel bug demo
===============
Parcel has issues importing raw assets into JS bundles if the file is referenced somewhere else.

To test this out, clone this repo, run `npm install`, then `npm start`, which will start Parcel's development server. Open your browser at http://localhost:1234 and open your console. It should show an error.