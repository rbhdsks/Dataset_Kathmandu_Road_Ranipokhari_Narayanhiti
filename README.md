# Kathmandu Road Dataset: Ranipokhari to Narayanhiti Durbar Museum

## Overview

This dataset contains annotated images collected along the route from Ranipokhari to Narayanhiti Durbar in Kathmandu, Nepal. It supports applications such as object detection, traffic monitoring, autonomous driving research, and smart city initiatives.

## Dataset Information

- **Location:** Kathmandu, Nepal
- **Route Covered:** Ranipokhari to Narayanhiti Durbar
- **Number of Images:** 146
- **Image Resolution:** 1920x1080 pixels
- **Annotations:** Bounding boxes and class labels

## Dataset Structure

```
Kathmandu_Road_Ranipokhari_Narayanhiti/
├── IMG_2082/
│   ├── frame_00000.jpg
│   ├── frame_00077.jpg
│   └── ...
├── labels/
│   ├── frame_00000.xml
│   ├── frame_00077.xml
│   └── ...
└── README.md
```

## Annotation Classes

The dataset annotations include the following object classes:

- `vehicles`
- `pedestrians`
- `traffic_signs`
- `traffic_signal`
- `car`
- `motorcycle`
- `bus`
- `truck`
- `animal`
- `other_vehicles`
- `auto_rickshaw`
- `cycle`

## Quick Example

Example Python usage:

```python
import cv2

image = cv2.imread('IMG_2082/frame_00000.jpg')
# Annotation processing from XML file
```

## License

This dataset is licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Proper attribution is required.

## Citation

Please cite this dataset as:

```
@misc{Maurya2025,
  author = {Nitesh Kumar Shah and Gadde Jahnavi and Chandra Prakash Maurya and Navjot Singh and Kartikeya Gullapalli},
  title = {Kathmandu Road Dataset: Ranipokhari to Narayanhiti Durbar},
  year = {2025},
  url = {https://github.com/rbhdsks/Kathmandu_Road_Ranipokhari_Narayanhiti}
}
```

## Contributors

- **Nitesh Kumar Shah**, Student, IIIT Allahabad ([iib2021002@iiita.ac.in](mailto:iib2021002@iiita.ac.in))
- **Gadde Jahnavi**, Student, IIIT Allahabad ([iit2021190@iiita.ac.in](mailto:iit2021190@iiita.ac.in))
- **Kartikeya Gullapalli**, Student, University of Texas, Austin
- **Chandra Prakash Maurya**, Research Scholar, IIIT Allahabad ([prf.cpm@iiita.ac.in](mailto:prf.cpm@iiita.ac.in))
- **Prof. Dr. Navjot Singh**, Assistant Professor, IIIT Allahabad ([navjot@iiita.ac.in](mailto:navjot@iiita.ac.in))

---

Thank you for your interest in our dataset. Feedback and contributions are greatly appreciated!

