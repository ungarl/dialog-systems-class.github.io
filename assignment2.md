---
layout: default
img: TensorFlow.png
caption: TensorFlow
title: Homework 2 "TensorFlow"
active_tab: homework
release_date: 2017-01-17
due_date: 2017-01-26T14:00:00EST
---

<!-- Check whether the assignment is up to date -->
{% capture this_year %}{{'now' | date: '%Y'}}{% endcapture %}
{% capture due_year %}{{page.due_date | date: '%Y'}}{% endcapture %}
{% if this_year != due_year %} 
<div class="alert alert-danger">
Warning: this assignment is out of date.  It may still need to be updated for this year's class.  Check with your instructor before you start working on this assignment.
</div>
{% endif %}
<!-- End of check whether the assignment is up to date -->

<div class="alert alert-info">
This assignment is due before {{ page.due_date | date: "%I:%M%p" }} on {{ page.due_date | date: "%A, %B %-d, %Y" }}.
</div>


Learning TensorFlow  <span class="text-muted">: Assignment 2</span> 
=============================================================

The point of the first assignment is to get to acquainted with TensorFlow. In the Alexa Prize we want to design a deep learning social bot. The second step is to be able to train a seq2seq model. This involves installing TensorFlow and then training the first models. This code will probably not be the base of your model, but be a start to understand seq2seq models and model training in TensorFlow.

You should be excited about this assignment! You will be able to chat with your own bot!

Be creative and have fun.
 

1. Install TensorFlow on your computer, or somewhere where you have FREE personal access.
2. Train an XOR model. Test our several variants and use TensorBoard. What issues did you have? Which activation functions did you try? Which loss functions? What architectures did you try? What were the different results? How long did it take? 
3. Start a AWS instance with TensorFlow installed. See [https://github.com/ritchieng/tensorflow-aws-ami](https://github.com/ritchieng/tensorflow-aws-ami).
3. Train the seq2seq model on English to French translation. Follow [https://www.tensorflow.org/tutorials/seq2seq/](https://www.tensorflow.org/tutorials/seq2seq/).
4. Train seq2seq using chat data. TBD dataset, likely [https://github.com/suriyadeepan/datasets/tree/master/seq2seq/twitter](https://github.com/suriyadeepan/datasets/tree/master/seq2seq/twitter).
5. Submit homework [https://goo.gl/forms/hZuE9ubmVAUFxwQh2](https://goo.gl/forms/hZuE9ubmVAUFxwQh2).