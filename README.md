# certificate-forgery-detection-using-deep-learning-and-django
This project is a web-based certificate verification system built with Django and powered by a Deep Learning model to detect forged or manipulated certificates. The system provides an automated, accurate, and reliable way to verify certificate authenticity.

**🔹 Features**

Upload and verify certificates in real-time

Deep Learning model (CNN/transfer learning) to detect forgery in certificate images

Preprocessing techniques (image resizing, normalization, OCR if required)

Admin panel for managing certificate datasets and records

Secure storage and verification of genuine certificates

User-friendly web interface with Django templates

**🔹 Tech Stack**

Backend: Django, Python

Frontend: HTML, CSS, Bootstrap

Database: SQLite / PostgreSQL

Deep Learning: TensorFlow / Keras / PyTorch

Other Tools: OpenCV, Pillow (image preprocessing), Numpy, Pandas

**🔹 Workflow**

User uploads a certificate image.

Deep Learning model analyzes the image for tampering or forgery.

The system cross-checks the uploaded certificate against the stored database.

Results are shown as “Authentic” or “Forged” with confidence score.

**🔹 Use Cases**

Universities & Colleges for validating student certificates

Employers to verify candidate qualifications

Government and organizations to prevent fake document submission
