# Sequential GeoJson

## Status

This not-yet module currentrly only works on GeoJson files that contain one single FeatureCollection. It returns found features as a string.

## Usage

Create a new reader object `reader = sequentialGeojson.reader( myPythonFileObject )`.

Then use this reader as you would use any generator. With each step it returns one single feature as a string.

