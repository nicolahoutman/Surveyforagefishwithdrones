# Surveyforagefishwithdrones
Surveying forage fish with drones
Data associated with paper to be published by Houtman et al. 
Data field descriptions:
School ID: Unique identifier for each school detected in drone imagery
Survey ID: Identifies which survey each school was detected in. The first 6 digits show the date (YYMMDD), which is followed by the site name where the survey was conducted (the name of a geographic feature), the drone name used to survey (Mavic 2 pro, M2P, or Phantom 4, P4), and then the chronological number of that survey for each date (first survey of the day =01, second = 02 etc.)
Time: The time of day that fish school was captured in the survey
Latitude and longitude: Location of the center of imagery frame that the fish school was detected in (not exact as fish schools were not always in the center of the video frame, and coordinates are subject to GPS inaccuracy)
AS: Adjusted Secchi depth (m) as described in the paper
CC: cloud cover (%) as described in paper
WH: Wave height (cm) as described in the paper
WS: Wind speed (km/hr) as described in the paper
SA: Sun altitude (degrees) as described in the paper
Saz: sun azimuth (degrees) - position of the sun on the sun measured in degrees from north. Recorded from the same online NOAA calculator as Sun altitude. 
TH: Tidal height (m) as described in the paper
CSD: confidence in school detection as described in the paper. Classified as high, medium, or low
CSD_number: number corresponding to CSD classification. H= 3, M= 2, L=1
School_size: Estimated number of individual fish in each school
School_bin and School_size_name: school sizes were binned according to a Jenks Natural breaks algorithm. These fields show if the school was considered small=1, medium = 2, or large = 3
Contrast: Contrast between the school and the background classified as high or low
Contrast_number: number corresponding to high = 2, and low = 1 contrast 
Bottom_type_tone: additional information recorded for school. Refers to the tone and type of bottom that each fish school was seen over. Tone could be light, medium, dark, or mixed, while type could be vegetation, sand, mixed, or rock.
