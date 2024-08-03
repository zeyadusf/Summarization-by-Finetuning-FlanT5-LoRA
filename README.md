<div align='center'>
  
# Summarization Task by Finetuning Flan-T5 with PEFT and LoRA

<img src="https://github.com/user-attachments/assets/91864846-8c24-4e2b-a7bf-dbaf3f941779" width="600" alt="Flan T5">

</div>

"Summarization Task by Finetuning Flan-T5 with PEFT and LoRA" involves using the Flan-T5 model, a variant of the T5 model designed for various NLP tasks, to generate concise summaries from longer texts.by use Parameter-Efficient Fine-Tuning (PEFT) and Low-Rank Adaptation (LoRA) techniques to fine-tune the model efficiently, possibly reducing the number of parameters required and speeding up the training process. 

* training on SAMSum dataset contains about 16k messenger-like conversations with summaries. Conversations were created and written down by linguists fluent in English.
  <br>
🔗 [samsum](https://huggingface.co/datasets/Samsung/samsum)
<br>

🔗 **Can access model through huggingface**
[FlanT5Summarization-samsum](https://huggingface.co/zeyadusf/FlanT5Summarization-samsum) 
<br>

🔗 **Notebook on Kaggle** 
[Summarization by Finetuning FlanT5-LoRA](https://www.kaggle.com/code/zeyadusf/summarization-by-finetuning-flant5-lora)

*You can know the hyperparameters through huggingface and kaggle*
<hr>

🚩 **Can use model through Space** [Summarizationflant5](https://huggingface.co/spaces/zeyadusf/Summarizationflant5)
### Examples

```dialogue: 
Emma: Hi neighbour :)
Emma: Do you want to take a stroll with the little ones?
Abigail: Hey Emma :) I don't think that's a good idea.
Abigail: My smog alert app is showing that the norms have been exceeded by 30% today :O
Emma: Oh my, that sounds serious.
Emma: I need to install that app.

flan-t5-base summary:
Abigail doesn't want to take a stroll with the little ones because of the smog alert app. Emma needs to install the app.
Abigail's smog alert app shows that the norms have been exceeded by 30% today.
```
```dialogue: 
Stefano: Hi, Josie!
Josie: Ciao, Stefano!
Stefano: So, what about Foucault's Pendulum? Do you like it?
Josie: It's... weird. Was it really written by an Italian guy? It's so... nerdy.
Stefano: Oh well, in a sense Eco was the king of nerds. And, you know, not all Italian books are about pizza, mafia and mandolino. :P
Josie: Yes, I know... I should try and read one of his novels in the original, but I'm not sure my level of Italian is adequate.
Stefano: The Name of the Rose is really difficult for a foreign speaker of Italian, you know.
Josie: And what about Foucault's Pendulum?
Stefano: Well, it's set in the 1980s, so the language is definitely more comprehensible. The content, however,
is just as complicated as in the other novel.
Josie: Btw, I read Salman Rushdie's review of Pendulum, published in the 80s.
Stefano: Really? What did he say?
Josie: He hated it and said that it's not a novel, but rather a computer game.
Stefano: What? Rotfl!
Josie: That's what Salman said...
Stefano: Oh well, de gustipus non est disputandum...
Josie: De gustiBus!
Stefano: I know, it was a typo!
Josie: Disgusting pus!
Stefano: Hahaha.
Josie: Yuk! That's so creepy.
Stefano: You're the one who said it!
Josie: I know. ;)

flan-t5-larg summary:
Stefano and Josie are discussing books. Josie thinks that Foucault's Pendulum is weird and that it's written by an Italian guy.
 Stefano thinks that the language is more comprehensible for a foreign speaker of Italian. Josie reads a review of Pendulum by Salman Rushdie.
```
<b>also can summary essays</b>

```essay
**Low-Rank Adaptation (LoRA)** and **Parameter-Efficient Fine-Tuning (PEFT)** are techniques designed to fine-tune large pre-trained models efficiently,
often with fewer computational resources and less data than full fine-tuning would require.

### LoRA (Low-Rank Adaptation)
LoRA is a technique that aims to reduce the number of parameters needed for fine-tuning large models. It does this by injecting low-rank matrices into the model's layers, which adjust the model's weights in a more efficient manner. By representing the updates to the weights with low-rank matrices,
LoRA reduces the computational and memory requirements during fine-tuning, making it more accessible for those with limited resources.
This approach also helps in situations where training data is limited, as it requires fewer parameters to learn effective task-specific adaptations.

### PEFT (Parameter-Efficient Fine-Tuning)
PEFT encompasses a broader range of techniques, including LoRA, that focus on fine-tuning pre-trained models in a way that is efficient both in terms of parameters and computational resources. The primary goal of PEFT is to adapt large models
to new tasks without needing to update all the model parameters, which can be costly and impractical for very
large models. Techniques under PEFT often include:

1. **Adapter Layers**: Adding small neural network layers that are inserted between the layers of the pre-trained model,
 allowing fine-tuning with only these additional parameters being updated.
2. **Feature-based Fine-Tuning**: Using features extracted from pre-trained models and training a smaller model or a classifier on top of these features.
3. **Subnetwork Activation**: Activating and fine-tuning only a subset of the model's parameters.

By using these approaches, PEFT aims to maintain the performance benefits of large models while reducing the cost and complexity of fine-tuning for specific tasks.

flan-t5-larg summary:
**Low-Rank Adaptation** and **Parameter-Efficient Fine-Tuning** are techniques designed to fine-tune large pre-trained models efficiently,
 often with fewer computational resources and less data than full fine-tuning would require.
 **LoRA** is a technique that aims to reduce the number of parameters needed
for fine-tuning large models.
```
<!--Social Media-->
<hr>

# :email: Contact #

<p align="center">
 <a href="https://www.facebook.com/ziayd.yosif" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-1877F2?style=flat&logo=facebook&logoColor=white" alt="Facebook" />
</a>

<a href="https://www.instagram.com/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-zeyadusf-white?style=flat&logo=instagram&logoColor=#E65468" alt="Instagram" />
</a>


<a href="https://www.linkedin.com/in/zeyadusf/" target="_blank">
  <img src="https://img.shields.io/badge/-Zeyad Usf-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

<a href="https://github.com/zeyadusf" target="_blank">
  <img src="https://img.shields.io/badge/-@zeyadusf-181717?style=flat&logo=github&logoColo
