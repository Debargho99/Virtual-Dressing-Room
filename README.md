# Virtual-Dressing-Room

This project demonstrates how to use AI to visualize how clothes fit on a person using Python and deep learning. The project uses DensePose from Detectron2 for detailed body surface estimation and maps the clothes onto the person using UV coordinates, providing a more accurate overlay.

## Project Structure

```plaintext
ai_clothes_fit/
│
├── app/
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css
│   │   └── uploads/
│   ├── templates/
│   │   └── index.html
│   ├── init.py
│   └── routes.py
├── model/
│   └── pose_estimation.py
├── images/
│   ├── sample_person.jpg          # Sample image of a person
│   └── sample_clothes.png         # Sample image of clothes (transparent background)
├── run.py                 # Entry point to run the Flask application
├── requirements.txt        # Required libraries
└── README.md               # Project documentation

└── README.md               # Project documentation
 clothes (transparent background)
├── run.py # Entry point to run the Flask application
├── requirements.txt # Required libraries
└── README.md # Project documentation
