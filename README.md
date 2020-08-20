# geotag
 - match - Main function of the repo for now; creates a dataframe of gps points their  matched frame filenames, the frames themselves are not geotagged yet
# videoToolkit
A couple of functions I made packed into one script
 - getCreationDate - Gets creation date of a video from exif tag "TrackCreateDate"
 - getOffsets - gets offset in ms from 0th frame to current frame (mostly used for other functions)
 - getTimestamps - Generates a CSV containing each frame of a video and its respective timestamp
 - createFrames - Generates a jpg image for every frame of a video
# trackToolkit
 - trackExtract - parses csv and gpx input and stores in a dataframe


# Notes
- Soon I will add ability to call each function from command line but for now you can only access getTimestamps
- Will add function that splits video up into frames then adds timestamp from getTimestamps to each picture
  
