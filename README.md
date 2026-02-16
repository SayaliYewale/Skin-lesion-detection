A comprehensive web application for early detection and classification of skin lesions using deep learning. Built with Django, it uses Convolutional Neural Networks (CNNs) to predict whether a lesion is present and identify its type. The app download a PDF report of the prediction.

A) Features:

1.Skin Lesion Detection – Identifies if a lesion exists (binary classification).

2.Lesion Type Classification – Classifies the lesion into one of 7 types (e.g., Melanoma, NV, BKL, etc.) using the HAM10000 dataset.

3.Image Upload Interface – Users can upload images directly from the browser.

4.Downloadable PDF Report – Generate and download a prediction report.

5.User Authentication – Includes login, signup, and logout features.

B) Technologies Used:

1.Backend: Python, Django

2.Deep Learning: TensorFlow / Keras (CNN models)

3.Frontend: HTML, CSS, Bootstrap

4.PDF Reports: ReportLab / xhtml2pdf

5.Dataset: HAM10000

End of the project