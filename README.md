# PoS-tagging

Implementation of a Part of Speech tagging system which make use of Custom word embeddings.

The word embeddings are generated using GenSim and the brown corpus provided by NLTK

PoS tagging is done on the Conll2000 dataset and the results achieved are as follows:

<table>
<tr>

<th>Model type</th>
<th>Accuracy</th>
</tr>
<tr>
<td>LSTM with single word context</td>
<td>85%</td>
</tr>

<tr>
<td>LSTM with five word context</td>
<td>91%</td>
</tr>
</table>
