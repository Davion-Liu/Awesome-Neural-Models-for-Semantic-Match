<div align="center">
<img width="300" src="artworks/awesome.svg" alt="Awesome">
<br>
<br>
<p><b>Awesome Neural Models for Semantic Match</b></p>
</div>
<br>
<p align="center">
<sub>A collection of papers maintained by MatchZoo Team.</sub>
<br>
<sub>Checkout our open source toolkit <a href="https://github.com/faneshion/MatchZoo">MatchZoo</a> for more information!</sub>
</p>
<br>

Text matching is a core component in many natural language processing tasks, where many task can be viewed as a matching between two texts input.

<div align="center">
<img width="300" src="artworks/equation.png" alt="equation">
</div>

Where **s** and **t** are source text input and target text input, respectively. The **psi** and **phi** are representation function for input **s** and **t**, respectively. The **f** is the interaction function, and **g** is the aggregation function. More detailed explaination about this formula can be found on [A Deep Look into Neural Ranking Models for Information Retrieval](https://arxiv.org/abs/1903.06902). The representative matching tasks are as follows:

<table>
<tr>
<th width=30%, bgcolor=#999999 >Tasks</th> 
<th width=20%, bgcolor=#999999>Source Text</th>
<th width="20%", bgcolor=#999999>Target Text</th>
</tr>
<tr>
<td align="center", bgcolor=#eeeeee> Ad-hoc Information Retrieval </td>
<td align="center", bgcolor=#eeeeee> query </td>
<td align="center", bgcolor=#eeeeee> document (title/content) </td>
</tr>
<tr>
<td align="center", bgcolor=#eeeeee> Community Question Answer </td>
<td align="center", bgcolor=#eeeeee> question </td>
<td align="center", bgcolor=#eeeeee> question/answer </td>
</tr>
<tr>
<td align="center", bgcolor=#eeeeee> Paraphrase Indentification </td>
<td align="center", bgcolor=#eeeeee> string 1 </td>
<td align="center", bgcolor=#eeeeee> string 2 </td>
</tr>
<tr>
<td align="center", bgcolor=#eeeeee> Natural Language Inference </td>
<td align="center", bgcolor=#eeeeee> premise </td>
<td align="center", bgcolor=#eeeeee> hypothesis </td>
</tr>
</table>


### Healthcheck

```python
pip3 install -r requirements.txt
python3 healthcheck.py
```