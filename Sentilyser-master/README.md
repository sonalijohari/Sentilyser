# Sentilyser
Sentilyser, is built on python. Using feature extraction modules, features like frequency, pitch, speech rate etc are exploited
and these features are fed to a Support Vector Machine and the values of valence and arousal are calculated. These values are
then used to find the corresponding emotions using a k-nn classifier.

## Installation
 * Install dependencies:
 ```
pip install numpy matplotlib scipy sklearn hmmlearn simplejson eyed3 pydub
```






