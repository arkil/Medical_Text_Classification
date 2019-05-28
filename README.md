# Medical_Text_Classification


Medical abstracts describe the current conditions of a patient. Doctors routinely scan
dozens or hundreds of abstracts each day as they do their rounds in a hospital and must
quickly pick up on the salient information pointing to the patient’s malady. In the given dataset,
abstracts from 5 different conditions have been included:
digestive system diseases, cardiovascular diseases, neoplasms, nervous system diseases, and general pathological conditions.

The min-epsilon k-NN classifier is defined similarly as the k-NN classifier with the exception
that neighbors 2 to k are additionally restricted to have a minimum similarity of epsilon with
the query object. In other words, restrict neighbors by both number of neighbors and
minimum similarity, but always retrieve at least one neighbor. Given the retrieved
neighbors, you must still decide on the way you aggregate their labels to make the final
decision (e.g., majority count or weighted sum)

The training dataset consists of 14438 records and the test dataset consists of 14442
records
