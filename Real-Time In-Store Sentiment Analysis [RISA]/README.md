
# Real-Time In-Store Sentiment Analysis [RISA]

In-Store analytics is very important when it comes to understanding ->
- efficiently managing the product placements.
- optimizing store operations.
- how customers feel when they are inside the store.
- how customers feel when talking to a customer representative(rep).
- customers' overall shopping experience.
- personalizing marketing content and recommending relevant producsts
- etc.

Companies/Retailers have been using image/video analysis of in-store customers' interactions to get insights for the above tasks. But, most systems are batch-mode and not real-time. The primary use of real-time is to know instantly how the customer feels and change your course of action based on that. 


In this project we will build a Real-Time In-Store Sentiment Analysis system(RISA) to know more about customers's sentiments while they are inside the store. It is a two step process:-
- Step 1 - Collect facial data of customer (camera feed/Raspberry Pi etc.)
- Step 2 - Crop face from overall image to be fed to the sentiment classifier.
- Step 3 - The facial expression is then classified as one of the categories (Happy, Sad, Neutral etc.)
- Step 4 - After generating real-time insights of customer's sentiments, the store owner can work on cutomer loyalty and engagement programs. 





Prototyped Facial Expression Recognition system for in-store customer analytics.

Achieved 89% accuracy using OpenCV for detecting facial bounding boxes and TensorFlow for multi-class classification of expressions trained on FER-2013 dataset.


References:
https://www.icontroldata.net/blog/5-benefits-of-retail-analytics
