---
title: Perilaku Konsumen Wine di Jawa-Bali (Indonesian Viz)
tags: 
- Personal Project
- Tableau Desktop
- Tableau Prep
- Tableau Public
- Microsoft Excel
cover: /Demografi.png
---

Back in May, someone told me about a questionnaire that focuses on the demographic composition, behaviour, and sentiments wine consumers in Bali and Java. I found this topic to be interesting and challenged myself to present the findings in a way that makes the best use of the correspondent's answers. 

I aim to keep the visualisation clean and simple by using bar and tree charts, although I tried experimenting using modified butterfly charts to visualise the correspondent's sentiment regarding local wine, wine knowledge, and perception regarding wine for the final two dashboards of the workbook below.

<div class='tableauPlaceholder' id='viz1635843678775' style='position: relative'><noscript><a href='#'>
  <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pe&#47;PerilakuKonsumenIndonesianViz_16343684397670&#47;Demografi&#47;1_rss.png' style='border: none' />
</a>
</noscript>
<object class='tableauViz'  style='display:none;'>
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
  <param name='embed_code_version' value='3' /> 
  <param name='site_root' value='' />
  <param name='name' value='PerilakuKonsumenIndonesianViz_16343684397670&#47;Demografi' />
  <param name='tabs' value='yes' />
  <param name='toolbar' value='no' />
  <param name='display_count' value='yes' />
  <param name='language' value='en-GB' />
  <param name="dataDetails" value="no" />
  <param name="alerts" value="no" />
  <param name="showShareOptions" value="false" />
  <param name="subscriptions" value="no" />
  
</object>
</div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1635843678775');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='850px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='850px';} else { vizElement.style.width='100%';vizElement.style.height='2000px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I initially used Tableau Prep to clean and transform the data. However, I eventually found the cleansing process to be challenging due to the open-ended nature of some of the more important questions, such as favourite wine brand and consumer opinions regarding wine produced in Indonesia (referred to as 'local wine' in the questionnaire). 

At some point, I had to manually clean and extract the question's results in Microsoft Excel, before saving them as separate data sources from the main workbook. As these two questions focus on words and phrases, I decided to generate word clouds on Tableau.

<div class='tableauPlaceholder' id='viz1635909419951' style='position: relative'><noscript><a href='#'>
  <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wi&#47;WineQuestionnaire-MerkWineFavorit&#47;Dashboard1&#47;1_rss.png' style='border: none' />
</a>
</noscript>
<object class='tableauViz'  style='display:none;'>
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
  <param name='embed_code_version' value='3' /> 
  <param name='site_root' value='' />
  <param name='name' value='WineQuestionnaire-MerkWineFavorit&#47;Dashboard1' />
  <param name='tabs' value='no' />
  <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wi&#47;WineQuestionnaire-MerkWineFavorit&#47;Dashboard1&#47;1.png' /> 
  <param name='toolbar' value='no' />
  <param name='display_count' value='yes' />
  <param name='language' value='en-GB' />
  <param name="dataDetails" value="no" />
  <param name="alerts" value="no" />
  <param name="showShareOptions" value="false" />
  <param name="subscriptions" value="no" />
</object>
</div>                

<script type='text/javascript'>                    
var divElement = document.getElementById('viz1635909419951');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='800px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='800px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
<center>*Do you recognise some of these wine brands?*</center>

<div class='tableauPlaceholder' id='viz1635910813718' style='position: relative'><noscript><a href='#'>
  <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wi&#47;WineQuestionnaire-WordCloud&#47;WordCloud&#47;1_rss.png' style='border: none' />
</a>
</noscript>
<object class='tableauViz'  style='display:none;'>
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
  <param name='embed_code_version' value='3' /> 
  <param name='site_root' value='' />
  <param name='name' value='WineQuestionnaire-WordCloud&#47;WordCloud' />
  <param name='tabs' value='yes' />
  <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wi&#47;WineQuestionnaire-WordCloud&#47;WordCloud&#47;1.png' /> 
  <param name='toolbar' value='no' />
  <param name='display_count' value='yes' />
  <param name='language' value='en-GB' />
  <param name="dataDetails" value="no" />
  <param name="alerts" value="no" />
  <param name="showShareOptions" value="false" />
  <param name="subscriptions" value="no" />
</object>
</div>                

<script type='text/javascript'>                    
var divElement = document.getElementById('viz1635910813718');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='800px';vizElement.style.height='850px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='800px';vizElement.style.height='850px';} 
  else { vizElement.style.width='100%';vizElement.style.height='750px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>