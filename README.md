# TextToAudioBeta

### frontend
```
pod install
open ListenText.xcworkspace 
```

### backend
```
cd server
source env/bin/activate
python3 index.py (localhost:5000)
```

### api endpoints
```
/: main page
/test: received post request from frontend

```

### file structure
ListenText
    ├── ViewController.swift 
    ├── Main.storyboard
server
    ├── index.py
    ├── resource
    │   └── test_img.png
    ├── upload_to_bucket.py
	├── download_from_bucket.py
    └── vision_helper.py



