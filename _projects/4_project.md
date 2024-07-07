---
layout: page
title: ChessGPT
description: AI Chess Engine
img: assets/img/chess_demo.gif
importance: 3
category: fun
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/chess_demo_red.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An opening sequence against the Chess AI.
</div>


While tinkering with OpenAI's GPT2, I thought of experimenting with it to see how well it can assimilate chess games and then actually play afterwards. GPT-2 is a large language model capable of generating realistic text, and is often fine-tuned to accomplish other NLP tasks. In order to fine-tune it, a large dataset of sequences (sentences) is required so that the model can train on it and pick up relevant patterns. However, there's no strict requirement that the sequences should correspond to sentences of a particular language. In other words, in theory one can provide GPT2 with any dataset of sequences, and it will try to assimilate key patterns during the fine-tuning phase. Thus, as absurd as it might sound, it's actually possible to train GPT2 on chess games.

A chess game is after all nothing but a 'sequence' of moves. And this sequence can be digitally stored in the [UCI](https://en.wikipedia.org/wiki/Universal_Chess_Interface) format. Thanks to a lot of nice people, several large open-source databases of chess games stored in the UCI format have been uploaded online. I scraped several of these from the internet and combined them to form a large database of chess games. After that, I wrote the Python scripts for fine-tuning GPT2 and then let it train for some hours using Google Colab's GPU. For the model to choose its next move, I implemented a customised beam search algorithm which made the model explicitly predict the gameplay a certain number of moves ahead and then take its decision. I also integrated the model with an open source GUI so that once can actually play with it. 

The model currently manages to play a decent opening game, but struggles to play sensible moves thereafter. In the future it could be improved upon by a longer/different training method or by integrating it with heuristic approaches to avoid nonsensical moves.

You can cccess the code repository on Github [here](https://github.com/Vibhu04/ChessGPT).
