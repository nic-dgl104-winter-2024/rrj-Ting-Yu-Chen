# Research and Reflection Journal



## Week 8



### Activities:

#### RESEARCH A NEW LANGUAGE

Learn more about  programming languages -  [Lua](https://www.lua.org/)

- **What is the language used for?**

  Lua is an embeddable, extensible, lightweight language.Lua has a small and clean API, making it suitable for various applications, particularly those where a small and efficient scripting language is needed.

  It is a  general-purpose programming. Lua has implemented  for games , embedded systems and scripting environments.

- **Who uses the language?**

  - Scripting Environments

    Common usage is combine Nigx with Lua.Lua is utilized as a scripting language within the nginx environment to provide flexibility and extensibility in configuring and customizing the behavior of the web server such as Logical Processing and Log Control

  - Game Developers

    developers can create games by Lua.There are some famous examples such as Angry Birds which is mostly written in Lua and the mobile payment app -Venmo was built using Lua.

  - Software Developers

    Developers can use Lua to make code commucicate with GPIO.

- **What are some useful resources?**

- [Official Lua Website](https://www.lua.org/)

-  [Youtube - IOT with Lua](https://www.youtube.com/results?search_query=IOT+with+Lua)

- **Why are these specific resources useful?**

  1. [Official Lua Website](https://www.lua.org/)
     As a benginer offical website always has a good tortual to explain what is it about, and demstorate basic exampes
  2.  [Youtube - IOT with Lua](https://www.youtube.com/results?search_query=IOT+with+Lua) 
      When it comes to devices, situation become complex and it is hard to understand just by wordings.Thereby, programming for ITO purpose while watching a viedo step by step will make process efficient.

**Reflection:**

I have learned that it's possible to combine different languages for a project. I have experience with Raspberry Pi, where I coded to communicate with various devices like GPIO and a buzzer Back then, I had to use a substantial amount of code and might end up discovering that the device was not functioning.  Another significant takeaway is that in such cases, Lua proves to be a suitable language for quickly implementing requirements. For example, if we design a light bulb for a device and want to check if the bulb is working or not, Lua is an easy language to use for testing purposes.



#### CHOOSE A LANGUAGE FOR COMMUNITY CODE

I chose **[Dart](https://dart.dev/)** as my Community Code project language. I have 3 years of experience with Javascript, but it has mostly been limited to web development within browsers (although we can use Electron for desktop applications). Last year, I decided to expand my skills and explore a mobile language. I did consider native mobile languages such as Swift. However, I view mobile development as a secondary skill, so a native language would require too much effort than I expected. Initially, I learned React Native since it is based on Javascript. Later, I encountered some issues that the community had no plans to fix. Meanwhile, I discovered Flutter, created by Google. I found its coding approach interesting, and it is supported by many libraries. In a nutshell, I chose Dart for my assignment. Although I am still torn between Flutter and React Native, I can use this assignment to delve into Dart.



## Week 9

### Activities:

1. #### **READ “HOW TO CONTRIBUTE TO OPEN SOURCE”**

I used to search for issues for solutions and somtime comments under a issue to ask for help. I feel like someone being contributed to a project must be a expert, whcih I am still far away there. After reading this guide, I reilize that a densiner , a writer  and even a translator can also get involed with a project  and be part of members.Moreover, open source can also be a book and a recipe. What a fresh idea!

I choose Dart as I research langauge, and I am nearly newbie.Therefore finding issue or fix issue would be a tough chanellge for me. Hence I would like to fcus on document  or translation part, and standing on a shoe of a beginner , seeing what some information could be helpful.



- **FIND POTENTIAL PROJECTS TO CONTRIBUTE TO**

1. [bloc](https://github.com/felangel/bloc)
   It is definitely a plugin I would love to use for a Flutter project. The community is strong, and there are also translations available. 

   ![checklist_bloc](./assets/checklist_bloc.png)

2. [fl_chart](https://github.com/imaNNeo/fl_chart)

    I have been used [Apache ECharts](https://echarts.apache.org/) to deal with most of chart tasks on website. It works really well, and it provide many customized features. On the mobile side,  I am also wondering any customized charts available. Here is the libray I found most popular. However they don't support enough chart type , for example : gauge. Although I saw a issue with a request feature label about that but the issue has been opened sinc 2020.

   ![checklist_fl_chart](./assets/checklist_fl_chart.png)

3. [easy_localization](https://github.com/aissat/easy_localization)

   Support mutiple lanagues could be a easy task , as long as the libray is easy to use. So I am also look for a libriary that supports localization langaue. I found this libray although the starts is not much as popular one but their disccusion is active, and have some closed pull request few weeks ago.

4. [flutter_carousel_slider](https://github.com/serenader2014/flutter_carousel_slider)

   To be a attractive application, slider is good choose to go for. I also found the most popular slider libiray. However, this project seems not have active disscuion and the latest closed commit is at Jul 2, 2023.

   ![checklist_flutter_carousel_slider](./assets/checklist_flutter_carousel_slider.png)

- **IDENTIFY ISSUES TO SUPPORT**

  - bloc

    The documentation provided by the community for the Bloc is comprehensive. However, despite the presence of translation buttons on the official website, many translations remain unavailable.

  - fl_chart
  
    URL: https://github.com/imaNNeo/fl_chart/issues/1279
  
    **Description of the issue:**
  
    This feature request is about the ability to dynamically change the `tooltipBgColor` , customized the background color of tooltips based on the `y` value of the line in the chart such as a black background for points below 0 and a white background for points above 0. 
  
    **Where I would start:** 
  
    I believe this feature is essential. This presents an opportunity to explore the source code of the line chart. At least, I would take time to look at the code.
  
  - easy_localization
  
    I havn't acually really use this library, so document or fix bug colud cause too have loading for me.Maybe I could fcous on translation for their READM.md.
  
    

##### Reflection:

This week I try to get involve to be a contributor for a project. Significant takeaway here is I think I am getting into the flow different people contribute to a project. It is total refresh and cool for me.

#### Personal contributions on  [pattern library repository](https://github.com/nic-dgl104-winter-2024/pattern-library)

- [Add skeleton outline to README.md](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/16) 
- [Add JavaScript implementation for Singleton pattern](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/2)

##### Reflection:

I was not familiar with the actual workflow for contributions, but now I am getting used to it. Most of the time, I spend my time understanding the structure, and sometimes communication can take up half of the processing time to ensure everyone is on the same page.

After grasping the entire process, I started to learn the singleton pattern. Although I had learned this pattern before, I used this opportunity to review it. Initially, I preferred understanding the conditions under which I could use this pattern rather than focusing on how to write it. Since the reason I learn these patterns is to make my project more well-organized, there is no point in understanding a pattern without knowing how to use it. For this coding task, the first step is to analyze the real conditions under which I can implement the singleton pattern. The second step is to learn how to write the pattern, and finally, to implement the pattern in a real case.

## Week 10

#to be done

## Week 11

#to be done

## Week 12

#to be done



# Reference

[1] Cory Stieg (2022 11 06). Why Lua Is So Popular — & What You Can Build With It. Codecademy https://www.codecademy.com/resources/blog/what-is-lua-programming-language-used-for/