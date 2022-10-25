# IMSyPP-DATA

We present a Dutch social media dataset manually annotated for hate speech types and targets, created in the context of the [IMSyPP Project](http://imsypp.ijs.si/). The comments to be annotated were sampled from youtube, twitter and a variety of forums such as 4chan and dumpert. Two sets were annotated: a training set with 25,719 messages (IMSyPP_NL_train.csv) and an evaluation set with 2,858 messages (IMSyPP_NL_evaluation.csv). The dataset was annotated by 9 annotators with each comment being annotated by at least two annotators. It was used to train a classification model for hate speech type and target detection that is publicly available at the following URLs:

https://huggingface.co/IMSyPP/hate_speech_nl

https://huggingface.co/IMSyPP/hate_speech_targets_nl

The dataset consists of the following fields:
+ `URI` - The URL of the message
+ `doc` - text of the comment
+ `type` - type of hate speech
+ `target` - the target of hate speech