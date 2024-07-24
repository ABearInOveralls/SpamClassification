YouTube Comment Spam Classification

This project aims to classify YouTube comments as either spam or not spam using a Naive Bayes classifier. The analysis is based on a public dataset of comments collected for spam research, composed of 1,956 real messages extracted from five popular music videos.

Dataset Description

The dataset consists of five CSV files containing comments from the following videos:

Psy (YouTube01-Psy.csv)

Shakira (YouTube05-Shakira.csv)

Eminem (YouTube04-Eminem.csv)

LMFAO (YouTube03-LMFAO.csv)

Katy Perry (YouTube02-KatyPerry.csv)

Each dataset contains the following attributes:

COMMENT_ID: Unique ID representing the comment

AUTHOR: Author ID

DATE: Date the comment was posted

CONTENT: The comment text

CLASS: Indicates whether the comment is spam (1) or not spam (0)

Model Description

The model uses a Multinomial Naive Bayes classifier to predict whether a comment is spam or not. The training datasets include comments from Psy, Shakira, Eminem, and LMFAO videos, while the test dataset includes comments from the Katy Perry video.

Conclusion

This project demonstrates the effectiveness of using a Naive Bayes classifier to identify spam comments on YouTube. The model's high recall for spam comments makes it a valuable tool for maintaining the quality of user-generated content on platforms with high user engagement.

License:
This project is licensed under the MIT License. See the LICENSE file for details.
