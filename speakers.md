---
layout: page
title: Speakers
css: "/assets/css/index.css"
---

<!-- <div class="list-filters">
  <a href="/escuelaverano2024/" class="list-filter">Home</a>
  <a href="/escuelaverano2024/speakers/" class="list-filter filter-selected">Speakers</a>
  <a href="/escuelaverano2024/program/" class="list-filter">Program</a>
  <a href="/escuelaverano2024/about/" class="list-filter">About</a>
</div> --> 
<!-- Commented above because it repeats the same function as the website navigation bar -->

<!-- Should eventually separate in tutorials/panelists/etc -->

<div class="tab-wrapper">
	<div class="tab">
	<button class="tablinks" onclick="openSection(event, 'Keynotes')"  id="defaultOpen"><strong>Keynotes</strong></button>
	<button class="tablinks" onclick="openSection(event, 'Tutorials')"><strong>Tutorials</strong></button>
	<button class="tablinks" onclick="openSection(event, 'Panels')"><strong>Panels</strong></button>
	</div>
</div>



<div id="Tutorials" class="tabcontent">
 <section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Sudipta Kar</h3>
      <h4>Senior Applied Scientist at Amazon AGI</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_sudipta.jpeg'| relative_url }}" align="left" alt="speaker_sudipta" hspace="10" />
     Sudipta Kar is a Senior Applied Scientist at Amazon AGI. He received his Ph.D. in Computer Science from the University of Houston in 2020 under the supervision of Thamar Solorio. His doctoral research focused on creative text analysis. Currently, he works on developing intelligent systems to enable seamless proactivity in smart voice assistants such as Alexa. His research interests include computational systems for low-resource languages, language models, and information extraction.  He has co-organized multiple natural language processing workshops and shared tasks, including BLP, CALCS, MultiCoNER, and SentiMix. Additionally, in 2023 he led the first NLP hackathon held in Bangladesh. 
		</section>
		<section id="additional-info">
      <h4>Tutorial title: The Power of Rewards - Reinforcing Language Models with Reinforcement Learning </h4>
	  Language models ranging from BERT to GPT have shown impressive performance on many natural language tasks through first self-supervised pre-training on large text corpora and then fine-tuning on downstream tasks or even with zero-shot or few-shot approaches. These models are also very powerful in solving multiple tasks. However, their capabilities are still limited as they lack a built-in reward signal to directly optimize for the end task objective or align to certain human preferences.On the other hand, Reinforcement Learning (RL) is another area in machine learning which is commonly applied to develop systems that improve over real-time feedback loops (such as games). Because it provides a framework for optimizing goal-directed behavior through rewards. In this tutorial, we will explore how reinforcement learning came into the play of language modeling and suddenly changed the game by reinforcing the representational power of large language models with the ability to more efficiently solve tasks requiring reasoning, planning, and knowledge. We will first provide background on contemporary language models and reinforcement learning fundamentals. Next, we will discuss techniques for applying policy gradient methods to fine-tune language models to maximize rewards from an environment. Attendees will learn how to practically apply RL to language tasks, understand tradeoffs between different algorithms, and gain insight into state-of-the-art research in this emerging field. 
		</section>
		<hr>
		<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Danae Sánchez</h3>
      <h4>Researcher at the University of Copenhagen</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_danae.jpeg'| relative_url }}" align="left" alt="speaker_danae" hspace="10" />
     Danae Sánchez Villegas is a postdoctoral researcher at the University of Copenhagen. She holds a Ph.D. and a Master's degree in Computer Science from the University of Sheffield and a Bachelor's degree in Computer Engineering from the Instituto Tecnológico Autónomo de México. Her research interests include multilingual natural language understanding, vision and language modeling, and computational social science. Danae has worked as a Research Associate in the Natural Language Processing Group at the University of Sheffield and as an Applied Scientist Intern at Amazon Alexa.
		</section>
		<section id="additional-info">
      <h4>Tutorial title: Exploring Transformers and Limitations in Language Modeling. </h4>
      This tutorial explores language modeling techniques in Natural Language Processing (NLP), covering key concepts from traditional approaches to Transformer architectures. Beginning with an introduction to NLP and language modeling, it delves into probabilistic language models and progresses to neural language models, emphasizing the significance of embeddings for semantic representation. Moving on to Transformer models, we will discuss key concepts such as multi-head attention mechanisms, masked language modeling, and encoder models. Additionally, the tutorial addresses the limitations of large language models, providing insights into challenges and considerations for leveraging these models effectively in practical applications.
		</section>
		<hr>
		<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Alham Fikri Aji</h3>
      <h4>Assistant Professor at MBZUAI, UAE.</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_aji.jpeg'| relative_url }}" align="left" alt="speaker_aji" hspace="10" />
     Dr. Alham Fikri Aji is an Assistant Professor at MBZUAI, holding a Ph.D. from the University of Edinburgh's Institute for Language, Cognition, and Computation. His doctoral research, supervised by Dr. Kenneth Heafield and Dr. Rico Sennrich, focused on enhancing the training and inference speed of machine translation. Dr. Aji's current research centers around multilingual, low-resource, and low-compute Natural Language Processing (NLP). His recent work has been in developing diverse multilingual large language models. and multilingual NLP resources, particularly for underrepresented languages, with a specific emphasis on Indonesian. Dr. Aji has worked at Amazon, Google, and Apple in the past. 
		</section>
		<section id="additional-info">
      <h4>Tutorial title: TBD </h4>
		</section>
	<hr>
	<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Víctor Mijangos</h3>
      <h4>Professor at UNAM, Mexico.</h4>
      <br />
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_victor.jpeg'| relative_url }}" align="left" alt="speaker_victor" hspace="10" /> 
		<br><br><br><br><br><br><br><br><br>
		</section>
		<section id="additional-info">
      <h4>Tutorial title: TBD </h4>
		</section>
</div>


<div id="Keynotes" class="tabcontent">
<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Diyi Yang</h3>
      <h4> Assistant Professor at Stanford</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_diyi.jpeg'| relative_url }}" align="left" alt="Diyi Yang" hspace="10" />
     	Diyi Yang is an assistant professor in the Computer Science Department at Stanford, affiliated with the Stanford NLP Group, Stanford HCI Group, Stanford AI Lab (SAIL), and Stanford Human-Centered Artificial Intelligence (HAI). Her research interest lies in Socially Aware Natural Language Processing, aiming to better understand human communication in social contexts and develop socially aware language technologies that enhance both human-human and human-computer interaction.
		</section>
	<hr>
  <section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Veronica Perez Rosas</h3>
      <h4>Researcher at the University of Michigan</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_veronica_perez.jpeg'| relative_url }}" align="left" alt="Veronica Perez Rosas" hspace="10" />
     She obtained her Ph.D. in Computer Science and Engineering from the University of North Texas in 2014. She is a Level I Researcher recognized by the National System of Researchers. Currently, she is a researcher at the University of Michigan, where she is a part of the Artificial Intelligence laboratory and the Inform Language and Information Technologies research group in the Department of Computer Science. Her research interests include natural language processing (NLP), machine learning, computational linguistics, and multimodal representations. Her research focuses on NLP applications, including automatic detection of misinformation, NLP in mental health, as well as the detection of human behaviors such as sentiment, deception, sarcasm, and affective response. More information about her research can be found at https://vrncapr.engin.umich.edu/.
	 </section>
	 <hr>
	<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Alexis Palmer</h3>
      <h4>Assistant Professor at the University of Colorado Boulder</h4>
      <br />
			<!-- Headshot image -->
			<img width="140" id="bio-image" src="{{'/assets/images/speakers/speaker_alexis.png'| relative_url }}" align="left" alt="Alexis Palmer" hspace="10" />
     	Alexis Palmer is a computational linguist and a professor in the Department of Linguistics at the University of Colorado Boulder. She studied English literature at the University of Michigan, and later earned both an MA and a PhD in computational linguistics from the University of Texas at Austin. Her main research interests include computational semantics, computational discourse, and the development and application of computational methods to support language documentation and revitalization.
		</section>
	<hr>
</div>


<div id="Panels" class="tabcontent">
  		<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Jocelyn Dunstan</h3>
      <h4>Assistant Professor at the Pontifical Catholic University of Chile.</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_jocelyn.jpeg'| relative_url }}" align="left" alt="speaker_jocelyn" hspace="10" />
     Jocelyn Dunstan is an Assistant Professor at the Pontifical Catholic University of Chile. She holds a Ph.D. in Applied Mathematics and Theoretical Physics from the University of Cambridge in the UK. She specializes in leveraging machine learning and natural language processing to address key challenges. Her research primarily revolves around clinical text mining and patient prioritization. In addition to her academic role at the Catholic University of Chile, she is actively engaged as a researcher at prominent institutions such as the Millenium Institute for Foundational Research on Data (IMFD) and the Advanced Center for Electrical and Electronic Engineering (AC3E). Further information about her group's work can be found on their webpage at pln.cmm.uchile.cl. 
		</section>
	<hr>
	<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Manuel Montes y Gomez</h3>
      <h4>Full Professor at INAOE, Mexico.</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_manuel.png'| relative_url }}" align="left" alt="speaker_jocelyn" hspace="10" />
     Manuel Montes-y-Gómez is Full Professor at the National Institute of Astrophysics, Optics and Electronics (INAOE) of Mexico. His research is on automatic text processing. He is author of more than 250 journal and conference papers in the fields of information retrieval, text mining and authorship analysis. <br> He has been visiting professor at the Polytechnic University of Valencia (Spain), and the University of Alabama (USA). He is also a member of the Mexican Academy of Sciences (AMC), and founding member of the Mexican Academy of Computer Science (AMEXCOMP), the Mexican Association of Natural Language Processing (AMNLP), and of the Language Technology Network of CONACYT. In the context of them, he has been the organizer of the National Workshop on Language Technologies (from 2004 to 2016), the Mexican Workshop on Plagiarism Detection and Authorship Analysis (2016-2020), the Mexican Autumn School on Language Technologies (2015 and 2016), and a shared task on author profiling, aggressiveness analysis and fake news detection in Mexican Spanish at IberLEF (2018-2021).
		</section>
	<hr>
	<section id="main-bio">
			<!-- h2: Tier-2 Headline (Not as important as the h1 header, but more than one allowed). -->
			<h3>Dr. Luciana Benotti</h3>
      <h4>Associate Professor at the National University of Córdoba and AI Researcher at CONICET, Argentina.</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_benotti.jpg'| relative_url }}" align="left" alt="speaker_benotti" hspace="10" />
     Luciana Benotti is an Associate Professor in Computer Science at the National University of Córdoba and a Researcher in Artificial Intelligence at CONICET, Argentina. Her research interests include different aspects of situated and interactive NLP, such as interpreting instructions in a dialogue, generating contextualized questions, and deciding when to speak in a dialogue system, among others. She is particularly interested in how linguistic and non-linguistic features contribute to the meaning conveyed during a conversation. These features include what the conversational participants are doing while they talk, the visual context, temporal aspects, etc. She has been a visiting scientist at the University of Trento (2019), Stanford University (2018), Roskilde University (2014), the University of Costa Rica (2012), and the University of Southern California (2010). She holds a joint MSc Erasmus Mundus from the Free University of Bolzano and the Polytechnic University of Madrid and a PhD from the Université de Lorraine. This year, she was chosen as the Latin American representative for the North American Association for Computational Linguistics (NAACL).
		</section>
		<hr>
		<section id="main-bio">
			<h3>Dr. Veronica Perez Rosas</h3>
      <h4>Researcher at the University of Michigan</h4>
      <br />
			<!-- Headshot image -->
			<img width="225" id="bio-image" src="{{'/assets/images/speakers/speaker_veronica_perez.jpeg'| relative_url }}" align="left" alt="Veronica Perez Rosas" hspace="10" />
     She obtained her Ph.D. in Computer Science and Engineering from the University of North Texas in 2014. She is a Level I Researcher recognized by the National System of Researchers. Currently, she is a researcher at the University of Michigan, where she is a part of the Artificial Intelligence laboratory and the Inform Language and Information Technologies research group in the Department of Computer Science. Her research interests include natural language processing (NLP), machine learning, computational linguistics, and multimodal representations. Her research focuses on NLP applications, including automatic detection of misinformation, NLP in mental health, as well as the detection of human behaviors such as sentiment, deception, sarcasm, and affective response. More information about her research can be found at https://vrncapr.engin.umich.edu/.
	</section>
	<hr>
</div>

<script>
// JavaScript for Tabs
function openSection(evt, sectionName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(sectionName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Open the first tab by default
document.addEventListener("DOMContentLoaded", function() {
  document.getElementById("defaultOpen").click();
});
</script>

<!-- <button class="tablinks" onclick="openSection(event, 'Tutorials')" id="defaultOpen">Bio</button> -->

