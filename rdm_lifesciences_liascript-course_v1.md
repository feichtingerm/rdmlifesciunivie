<!--
author:   Emily Jean Kate, Michael Feichtinger

email:    emily.jean.kate@univie.ac.at, michael.feichtinger@univie.ac.at

version:  1.0

language: en


comment:  Online self-study part of the RDM for the Life Sciences Workshop for Doctoral Candidates @ Centre for Microbiology and Environmental Systems Science and Faculty of Life Sciences, University of Vienna.
-->

## Orientation
Welcome to the Research Data Management Course for the Life Sciences! 
====================
We’re so glad you’re here. Since you found your way to this page, you must have signed up for the course via one of the University of Vienna Doctoral Schools associated with the Centre for Microbiology and Environmental Systems Science or the Faculty of Life Sciences.

Before we delve into the exciting world of Research Data Management (RDM), we want to make sure you know what you’ve gotten yourself into. Don’t worry. We removed most of the scary stuff during beta testing. 

Blended Learning and Our Plan
--------------------
This course is designed around a concept called “blended learning”, which is a fancy way of saying that we use both online and in-person learning resources. In our case, you will have until March 17th to complete the online modules here on Moodle. The Moodle portion of the course should take you around 2.5-3 hours and we recommend you complete the modules in-order but you don't have to do them all at once.
On March 18th and 19th (9:00-12:00 each day), we will meet in-person in UBB SR 1.6 (on the 18th) and UBB SR 1.5 (on the 19th) to delve deeper into the mysteries of RDM. Intriguing, we know.

![The Upturned Microscope](https://upmic.files.wordpress.com/2019/05/epfl-may2019-flipped-classroom.png?w=650&h=199 " [Flipped Classroom by Upturned Microscope](https://upmic.files.wordpress.com/2019/05/epfl-may2019-flipped-classroom.png?w=650&h=199),[CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/)")

Will We be Graded?
--------------------
Diligent student that you are, you may be wondering about assignments, quizzes, and grades. The simple answer is that there are no grades. You signed-up for this course because you have an interest in learning more about RDM. We agreed to teach the course because we like teaching about RDM and think students are the most fun to support. Throughout the Moodle modules, there are some self-knowledge quizzes. Most are multiple-choice and you can attempt them as often as you like. No one is keeping score. Actually, the code we used to build this course is digitally incapable of it.


![XKCD Priorities](https://imgs.xkcd.com/comics/priorities.png " [Priorities by XKCD](https://xkcd.com/336),[CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")


The Pre-Learning Assessment 
--------------------
With that said, there is one place where we will be recording your answers. That’s the prior knowledge assessment. **YOU SHOULD COMPLETE THE PRIOR KNOWLEDGE ASSESSMENT BEFORE DOING ANY OF THE COURSE MODULES.** This assessment allows us to track your knowledge level before you started the course, so that we can estimate what you have learned during your time with us. We know it might be tempting to reach for Google or ChatGPT while you fill-out the assessment, but please don’t! Just try to answer the questions. Your answers can be vague. “I don’t know the answer to this question” is even a valid response. Honestly, this assessment tests out abilities as educators, not your knowledge as a student.

The Course Map
--------------------
![Course Map](https://raw.githubusercontent.com/feichtingerm/rdmlifesciunivie/main/images/RDMCourseMap.jpg)

Bye! 
--------------------
If you have any questions during the course, please feel free to contact us! We would love to hear from you. See you soon!

Michael Feichtinger and Emily Kate
UNIVIE Data Stewards



## What is Research Data Management (RDM)?
In this section we discuss several topics linked to conducting your research in a well-planned and managed manner. We'll give some key definitions, tell you about the research data life cycle, and explain the FAIR principles and how they related to Open Science.   

Learning Objectives
================

1. Define research data management, research data, and metadata and explain why they are important. 
2. Explain the research data life cycle. 
3. Identify the FAIR principles and give a short description of each. 
4. Define Open Research and explain the benefits and challenges of Open Research and the FAIR Principles.

### Research Data
We all know what research data is, right? I mean, it’s data from research. The meaning is clear. Crisis averted. We can all go home. Or maybe not… The problem starts when we delve a little deeper into what we mean by “data”. 

The University of Vienna considers research data to be “all information (irrespective of its form or presentation) that supports or validates research activities (development, results, observations or findings, including contextual information). Research data comprise all materials that are created in the course of academic work, including records, source research, experiments, measurements, surveys and interviews, as well as software and code. Research data may take on various different forms: during the lifespan of a research activity, data may exist as gradations from raw data to processed data (and even include negative and inconclusive results)”.

What a mouthful, but the punchline is that your research data is a lot more than just the individual measurements you used to formulate your newest figure or validate your most recent hypothesis. Your research data certainly includes those things, but all information you create during the research process can be considered data too! Even your “negative results” are data. Not all data will be sent into the world as an open source dataset and that’s okay, but it doesn’t mean we shouldn’t give those tidbits as much care and attention as the other stuff. We’ll talk more about why some data shouldn’t be released into the wild a little later. 

Alright, now that we know what research data is, we can move onto that mysteriously bureaucratic phrase “research data management”. I bet the people who work in that department are a bunch of boring pencil pushers…oh wait…I’m being told we work in that department…but I’m not boring and I rarely push pencils. 


Research Data Management 
================
If you guessed that research data management involves the management of research data, you’re right, but you also just reorganized three words to create a less-than-specific definition. 
Again, the University of Vienna has a specific definition for research data management (RDM). Here it is in all its glory: 

“Given the heterogeneous nature of research data, research data management (RDM) may include different aspects depending on the relevant discipline. In general, RDM covers all research data during the entire research process, e.g. planning and generating data, documentation, data administration, secure storage, access management, as well as reuse, (long-term) archiving and access regulation. RDM should ensure that research data are effectively managed during the research project and that they are securely archived and made reusable after project completion…”

Our good friends at Ghent University are also really passionate about RDM and they created this great video that provides another perspective on what RDM entails. While you watch, we’re probably going to go call them…maybe invite them to brunch. 

!?[Ghent University Data Stewards (2020) Knowledge Clip: What is Research Data Management (RDM)](https://youtu.be/bbsLmy3Njv4 "[Ghent University Data Stewards 2020. Knowledge Clip: What is Research Data Management (RDM)](https://youtu.be/bbsLmy3Njv4), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Finished watching? So now you know that research data management means ensuring that your data are well organized, documented, securely stored, eventually archived, findable, and reusable by others whenever possible. This might seem overwhelming, but never fear! The Research Data Management Team at the University of Vienna is here to help. 

We have a handy website at rdm.univie.ac.at and you can email us anytime at rdm@univie.ac.at. If you or your friends are part of the Faculty of Life Sciences, the Centre for Microbiology and Environmental Systems Science, or the Faculty of Philological and Cultural Studies, you have a dedicated data steward who can help you too! Send a data steward or the RDM team an email with a question and we will get back to you within three working days. We’ll either answer your question or outline some next steps. 

Quiz 
======================
Alright, let's see what you've learned with a short quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

Only results underpinning research papers, or other outputs, are considered research data.

    [[ ]] True
    [[X]] False

Negative results are an important part of research data. 

    [[X]] True
    [[ ]] False

Research data management includes: 

    [[X]] Planning my research project
    [[X]] Documenting my data properly and thoroughly
    [[X]] Ensuring my data is safely stored
    [[X]] Managing who has access to my data even after my project is completed. 
    [[X]] Publishing my data. 
    [[X]] Placing my data in an archive. 
    [[X]] Deciding what data can be permanently deleted. 

What's a good source for RDM related advice and assistance at UNIVIE?

    [[ ]] The squirrels living in attic of UZA II might know something...
    [[X]] My faculty data steward 
    [[ ]] Google is my only hope. 
    [[X]] The UNIVIE RDM team and their nifty website

### Research Data Lifecycle

During the RDM video from the University of Ghent, you might have heard mention of the Research Data Life Cycle. The Data Life Cycle has seven stages that are pretty simple to understand. Way easier than remembering the cell cycle. The Data Life Cycle begins with the planning stages of your project and ends when your data is being re-used by someone else. In each of these stages, there are things you can do to care for your data and to encourage scientific cooperation.

![Research Data Life Cycle](https://github.com/elixir-europe/rdmkit/blob/master/images/data_life_cycle_9.png?raw=true "[Research Data Life Cycle by Elixir RDM Kit](https://rdmkit.elixir-europe.org/), [CC BY](https://github.com/elixir-europe/rdmkit/blob/master/LICENSE)") 

As you can see above, the stages of the Data Life Cycle are:

1. Planning 
2. Collecting 
3. Processing 
4. Analysing 
5. Preserving 
6. Sharing 
7. Reusing 

The cycle begins again when someone incorporates your data into their project or when you use data that was created by another researcher. Just remember PCPAPSR...XYZLMNOP...never mind. That's a terrible acronym. Actually, the best approach is for you to develop a good understanding of each stage in the research data life cycle. Watch this quick clip from the University of Ghent and then we will discuss each stage in more detail. By the end of this section, you should be able to explain the research data life cycle, but also think about how it relates to your work.    

!?[Ghent University Data Stewards (2020) Knowledge Clip: The Research Data Life Cycle](https://youtu.be/OL_Vd9dd-AQ "[Ghent University Data Stewards (2020) Knowledge Clip: The Research Data Life Cycle](https://youtu.be/OL_Vd9dd-AQ), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Step 1: Planning 
--------------------
Data management planning consists of defining the strategy that you will use for managing data and documentation generated within a project. It is about considering the best way to avoid problems or unexpected costs related to data management and setting-up your research data to achieve the highest possible impact in science, even after the end of the project.^1^ One of the most common ways to articulate this strategy is with a data management plan (DMP). You probably have questions about how to write a DMP, but we will cover that more in the next section. 

Step 2: Collecting
--------------------
Data collection is the process where information is gathered about specific variables of interest either using instrumentation or other methods (e.g. questionnaires, patient records). While data collection methods depend on the field and research subject, it is important to ensure data quality. Data collection could also mean reusing existing data in your project. This can either be individual earlier collected datasets, reference data from curated resources, or consensus data like reference genomes.^1^ We will talk more about reusing data in just a minute.

![The Upturned Microscope Change the Data](https://upmic.files.wordpress.com/2023/03/comic-14-change-the-data.png?w=650 " [Change the Data by Upturned Microscope](https://upmic.files.wordpress.com/2023/03/comic-14-change-the-data.png?w=650), [CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/)")

Apart from being the source of information to build your findings on, the collection phase lays the foundation for the quality of both the data and its documentation. It is important that the decisions made regarding quality measures are implemented, and that the collect procedures are appropriately recorded.^1^ When collecting data, you should ensure that whatever system you use does the following:  

* Captures important sample data like provenance of samples, their identifiers, the instruments used, and the researchers involved.
* Clearly defines the quality control standards you will use to assess data quality. 
* Details the experimental design of your project including information on important factors like repetitions, controls, and randomization. 
* Describes instrument settings and calibrations. 
* Adheres to any data protection, permission, or consent requirements within your project.
* Details how data will be stored, backed-up, and archived.
* Follows any discipline specific metadata standards. (More about this below!) 

Step 3: Processing 
--------------------
Data processing is the phase in the project where data is converted into a desired format and prepared for analysis. When data has been freshly collected, data processing includes some automated steps in a workflow that perform format conversions, quality checks, and preprocessing following a standardised protocol. The main aim of processing is to:

* Convert data into readable format, giving it the shape and form necessary for downstream analysis.
* Discard bad or low quality data in order to create clean, high-quality dataset for reliable results.

When data is imported from existing sources, e.g. data to be reused from another project, processing can also include manual steps to make it suitable for analysis. These steps include but are not limited to:

* Making changes to data formats such that different datasets will be compatible for integration with each other.
* Changing coding systems or ontologies for the data to bring everything to the same level; filtering data such that only data suitable for the project is retained.

After data processing, clean data is ready for analysis and should therefore be available to the members of the project team that need to perform the next steps. Data processing is important to ensure good quality of the collected data and to prepare it for meaningful data analysis. Accurate data processing is also essential for combining two or more datasets into a single dataset. An accurate documentation of every step done during data processing is key for the reproducibility of your result. Processing data correctly makes it easy to arrange, easy to analyse, and saves a lot of space.^1^

Also, remember that when you work with sensitive or protected data, you should pseudonymize/ anonymize your data during the processing phase. You should also use discipline specific methods of encoding variables if they are available, and you should keep careful records of how data was pseudonymized/ anonymized. It’s never a bad idea to also maintain a codebook where your variables are all explained. 

Step 4: Analyzing
--------------------
Data analysis begins when you finally dive into your data and use it to answer scientific questions or test hypotheses. The methods you use to analyze your data are also called a “workflow”. During many projects, workflows will likely be repeated several times and modified to increase reliability and efficiency. Always remember to keep clear records of how your workflow changes over time. You always want your workflows to be reproduceable by your team members and other researchers. This reproducibility is a central tenant of making science FAIR. Thinking about how you should analyze your data is obviously important, but you should also consider how you will document you analyses and investigations. 

Here are two last tips from people who know some things because they’ve seen some things and *occasionally* made mistakes themselves. First, always keep an unedited version of your unanalysed data stored. Never use this specific file to conduct analyses. Use a copy instead. This way, if you make a problematic edit to your data or your data gets jumbled, you can always make a copy of the original file and start again. This takes the situation from “data disaster” to an "inconvenient afternoon". Second, if you are conducting analyses and find yourself confused with a million files open and an inability to think clearly, it’s probably time for a break. Take a walk. Eat something. Have a nap. Drink some water. You aren’t going to make good analytical decisions when you’re frazzled, and you certainly won’t document things properly. A 30-minute break can save you hours of headache later. 

Step 5: Preserving
--------------------
When you hear of preserving, you might think of culinary delicacies such as smoked hams, canned pickles, or jarred jams. Sadly, this section will not be about any of those things. Data preservation is a process by which the safety, integrity, and accessibility of your data are ensured. In many cases, data should be preserved for years, or even decades. You might think that properly storing your data means it is preserved, but this is not quite the whole story. Preservation of digital information requires planning, policies, resources (time, funds, people) as well as the right technology to ensure that the data stays functional and that it can be accessed. Therefore, true data preservation, or archiving, must be done by experts and dedicated services. In most instances, special long term data repositories should be used for digital preservation, where the data is actively maintained and information integrity is monitored.^1^ 

![Trader Joe's Pickle Car](https://upload.wikimedia.org/wikipedia/commons/4/43/Trader_Joe%27s_-_Pickle_Car_%2812221274575%29.jpg "We know you also wish this section was about making pickles and other preserves. Sadly, it isn't, but maybe you could get yourself a pickle as a treat for making it this far.  [Source: Prayitno / Thank you for (12 millions +) view from Los Angeles, USA](https://upload.wikimedia.org/wikipedia/commons/4/43/Trader_Joe%27s_-_Pickle_Car_%2812221274575%29.jpg), [CC BY](https://creativecommons.org/licenses/by/2.0/deed.en)") 


The first step is data preservation is to decide what data should be maintained and what data can be destroyed. All (non-sensitive) data that contributed to a publication should preserved. In most cases, publishers and funding agencies will require that this data be made available. In many projects, researchers generate more data than they include in publications. This is where the decision-making process can be a little tricky. When considering if unpublished datasets should be preserved, researchers can ask themselves some critical questions. 

First, is the data in question high-quality, reproducible, and well documented? You should only archive unpublished data if the answer is a confident “yes”. Second, ask yourself if the data would be a new contribution to the scientific community and if it would be truly useful to another researcher. This is not to say that your experiment confirming the effectiveness of someone else’s method is valueless, but if you are the 275th researcher to make this conclusion, then the data is probably not worth archiving. Also, results from a smattering of disjointed or unorganized experiments are unlikely to be truly helpful. With this said, you should always think very critically about how data you produce might be useful and sometimes the answer is not easy to determine. In these instances, conversations with trusted colleagues and RDM experts can help you make a good choice. Here are few summarizing points about what should always be archived: 

* Data that must be published because of funder, publisher, or institutional policies. 
* Data that must be preserved due to legal or ethical requirements. 
* Unique data that cannot be easily re-created due to factors like high costs. 
* Data that will probably be reused. 
* Data that is of great cultural, historical, or scientific importance. 

You should also know that there is some data that should be destroyed as soon as possible. Usually, this data contains sensitive information, but never delete data without talking your supervisor! A little later, we will talk more about things like how to select a repository for your data and how long your data should be preserved. 

Step 6: Sharing 
--------------------
We all know that “sharing is caring”, but what does sharing mean in the context of research data management? Sharing data doesn’t mean that it is automatically open for others to use, but rather that your data is findable and that conscious choices have been made regarding who has access. You can actually share data at any time during the data life cycle and shift who can access the data as your project progresses. For example, you might share data with a collaborator or lab mates during the analysis phase but then place the data in an archive under a creative commons license once your papers are published. If you are thinking of sharing data, you should speak with your supervisor first, but here are some things to consider: 

* Are you the legal rights holder for the data? 
* Are there any ethical, legal, contractual, or intellectual property restrictions you need to consider? 
* Are there funder or institutional requirements that you are required to follow? 
* Consider what license you should use for your data based on your needs (more about this later).^1^

A little later in the course we will talk more about your data sharing and archiving options and how to select licenses for your data. If you have lots of questions, don’t worry. That’s completely normal.

Step 7: Reusing
--------------------
Data reuse means using data for other purposes than it was originally collected for. Reuse of data is particularly important in science, as it allows different researchers to analyse and publish findings based on the same data independently of one another. Data that is well-described, curated and shared under clear terms and conditions is more likely to be reused. Integration with other data sources is also important, since that can enable new, yet unanticipated, uses for the data.

Data reuse is important because it allows researchers to:

* Obtain reference data for research.
* Run analyses to verify that reported findings are correct, making subsequent findings more robust. 
* Gain novel insights through metanalyses.^1^

If you are considering reusing data, here are a few things you should do or consider:

* Explore different sources for reusable data. A starting point can be to look for value added databases with curated content. Other possibilities include searching data deposition repositories for suitable datasets based on their annotation, or obtaining data directly from the author of a scientific article.
* Check under which terms and conditions the data is shared. Make sure that there is a licence, and that the licence gives you permission to do what you intend. If there is no license or reuse statement, you cannot reuse the data.
* Check whether there is sufficient supporting information to enable data reuse. Some types of data can be straightforward to reuse, while other may require extensive metadata to interpret and reuse.
* Assess the quality of the data. Evaluate if the data comes from a trusted source and if it adheres to discipline standards. 
* Verify that the data has been ethically collected and that your reuse of the data conforms with policies and regulations you are expected to follow. For personal (sensitive) data, there are usually legal and technical requirements that have to be met before data can be accessed. Getting access to personal (sensitive) data will therefore involve additional steps.
* If the data you are reusing has been updated, make sure to document which version of the data you are using. Also consider what impact the changes may have on your results.
* Cite the data properly by include a persistent identifier (such as a DOI) in the citation, if there is one.^1^

You should think about all of these things when you reuse data, but they should also be considered when you make decisions about sharing and archiving your own work. Remember to set your data up for success so it can go into the world and do great things!

![XKCD Effect Size](https://imgs.xkcd.com/comics/effect_size.png "[Effect Size by XKCD](https://xkcd.com/2755), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

Quiz
================
Now it's time for you to check your understanding of the above-discussed topics with a short quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

Which stage of the Data Life Cycle involves defining the strategy for managing data and documentation?:

    [[X]] Planning
    [[ ]] Collecting
    [[ ]] Processing
    [[ ]] Analyzing

Data collection can also involve integrating previously generated data that came from sources beyond your own project or research group.

    [[X]] True
    [[ ]] False

Which type of data should always be archived?

    [[X]] Data required by funders or publishers
    [[X]] Data of great cultural, historical, or scientific importance
    [[ ]] Personal and/or sensitive data
    [[X]] Data that will likely be re-used
    
Sharing data means that everyone will have access to the data without restriction.

    [[ ]] True
    [[X]] False

### Metadata

In the words of Mugatu from the legendary film *Zoolander*, metadata is “so hot right now.” Despite its seemingly sudden popularity, you might be wondering how to define metadata and what it means for your research. The University of Vienna defines metadata as information that is “used to describe managed resources in a unique and structured manner. The unique structure enables users to search for, find and select relevant resources. Metadata are a means of communication between producers and users of research data, and are crucial for making data findable.” While accurate, perhaps this definition isn’t the most helpful for someone who is trying to figure how they can document their data more fully. To get a more hands-on explanation, take a look at this video from the University of Ghent.

!?[Ghent University Data Stewards (2020) Knowledge Clip: Metadata](https://youtu.be/DW2T_cnqKPU "[Ghent University Data Stewards (2020) Knowledge Clip: Metadata](https://youtu.be/DW2T_cnqKPU), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Essentially, metadata is data about your data and there are a few types of metadata you should think about: **administrative metadata**, **structural metadata**, and **descriptive metadata**. Let’s look at each type in a little more detail.

* **Administrative metadata** covers some technical and legal aspects of data creation and reuse. Administrative metadata of a technical nature often describes things like when files were created, the file types used, and how the files were created. Information about the owner and creator of the files can also be included here. On the more legal side, administrative metadata defines what license has been applied to a resource, how the resource can be reused, and how long and under what conditions the resource will be archived. 

* **Structural metadata** contains information about how a resource is organized and can also describe what one item’s relationship is to a larger collection. A book’s table of contents is a very good example of structural metadata. The table of contents tells you the book’s title, the names of the chapters, and their page numbers. It also points you to supplemental resources like the bibliography or index. A statement on the front cover of a book that tells you that it is part of a larger series can also be considered structural metadata. 

* **Descriptive metadata** is the largest category of metadata. In short, descriptive metadata ensures that an item is findable and interpretable. For example, in a library a book’s topic and unique call-number can be used to quickly locate it on the shelves. If data is archived online, a unique persistent identifier like a DOI might be used to ensure that resources can always be found again. Descriptive metadata might also include explanations of column headings or controlled vocabularies that have been used to describe observations. 

When you upload data to an archive or publish a paper you submit most of this information to the repository or publisher. In the best systems, this information is made machine-readable and can be picked-up by services like search engines so that your data doesn’t get lost in the chaos that is the internet. Because metadata documents important attributes of your data and makes it findable, it is important that metadata creation be handled with care and consideration! 

### FAIR data principles
The FAIR Principles were designed to support the sharing of research data. The intention of these principles is to improve the Findability, Accessibility, Interoperability and Reusability of data. 

At the heart of FAIR Science lies good data management practice. This is increasingly important as life science research becomes data-intensive and traditional ‘wet labs’ make space for ‘dry (computational) labs’.

The increasing volume, complexity and speed of data creation has made scientists rely on computational support exponentially. Therefore, the FAIR Principles place specific emphasis on enhancing the ability of machines to automatically find and use data, as well as supporting its reuse by other scientists, which facilitates knowledge discovery and improves research transparency^1^.

To learn a bit more about the FAIR principles, check out this clip from the University of Ghent. Then we will briefly summarize before moving onto the next section. Onwards! 

!?[Ghent University Data Stewards (2020) Knowledge Clip: FAIR data principles](https://youtu.be/2uZxFu9SFi8 "[Ghent University Data Stewards (2020) Knowledge Clip: Fair data](https://youtu.be/2uZxFu9SFi8), [CC BY](https://creativecommons.org/licenses/by/3.0/legalcode)") 

Findable
================

The first step in (re)using data is to find them. Metadata and data should be easy to find for both humans and computers. Machine-readable metadata are essential for automatic discovery of datasets and services, so this is an essential component of the FAIRification process.^2^ Data and their metadata should always be assigned a persistent unique identifier, like a DOI and this identifier should always be included in the metadata of an archived item. Data should also always be described by rich metadata that follows discipline specific standards whenever possible.  

Accessible
================

For data to be accessible, how data can be axquired should be clear to others. This does not mean that everyone can access all archived data all the time. It simply means that who can access data and how it can be accessed is clear. All data the underlies a publication should be freely accessible unless there are legal or ethical reasons why it cannot be shared. Even if data are sensitive, there should be a clear protocol regarding how access can be requested. Furthermore, the metadata should always be open and accessible so that other researchers can find the data and estimate if it may be useful to them prior to requesting access. 

![FAIR Data Principles](https://www.ugent.be/img/doza/beleid/rdm/fair-data.png "[Image by Patrick Hochstenbach](https://www.ugent.be/img/doza/beleid/rdm/fair-data.png), [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)")

Interoperable
================
When data is interoperable, it can be effectively combined with other datasets. This means that data is described in enough detail that other researchers will be able to assess the data’s quality and will be able to confidently combine it with other equally standardized datasets. File type is also an import part of interoperability. You may have the best organized and documented data in the world, but if it is stored in proprietary file type that no one else can open, it won’t be of much use. Because of this, you should always opt for non-proprietary file types whenever possible. 

Reuseable
================
We discussed reusability a lot when we covered the research data life cycle, so we won’t be labor it here. In addition to making sure that your data is well documented and in an appropriate file format, a license should also be applied to your data or code that explains under what conditions your materials can be re-used. Remember that you should almost always assign a license. If no license is assigned, then the materials cannot be reused. We’ll talk more about picking an appropriate license a little later. 

If you are especially curious about how to make your data FAIR and about how FAIR data supports Open Science, you can check-out the [go-fair.org](https://www.go-fair.org/fair-principles/) website on the FAIR principles or read [Wilkinson et al.’s 2016](https://doi.org/10.1038/sdata.2016.18) paper on the FAIR principles and data stewardship. 

### Open Research

Over the past few pages we have talked a lot about the RDM, the research data life cycle, and the FAIR principles. All of these concepts move us closer to open research. Open research aims to transform research by making it more reproducible, transparent, reusable, collaborative, accountable, and accessible to society. It pushes for change in the way that research is carried out and disseminated by digital tools. One definition of open research, as given by the Organisation for Economic Co-operation and Development (OECD), is the practice of making “the primary outputs of publicly funded research results – publications and the research data – publicly accessible in a digital format with no or minimal restriction.” To achieve this openness in research, each element of the research process should:

* **Be publicly available:** It is difficult to use and benefit from knowledge hidden behind barriers such as passwords and paywalls.

* **Be reusable:** Research outputs need to be licensed appropriately, so that prospective users know any limitations on re-use.

* **Be transparent:** With appropriate metadata to provide clear statements of how a research output was produced and what it contains.

![Fig.11 Turing Way Project](https://the-turing-way.netlify.app/_images/evolution-open-research.png "[Fig. 11 Turing Way Project](https://the-turing-way.netlify.app/_images/evolution-open-research.png), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)")

There are several schools of thought motivating open research practices, but they are not mutually exclusive. In fact, they are highly compatible. Here are just a few common beliefs surrounding open research and their goals^3^: 

| Belief   | Goal     |
| -------- | -------- |
| Efficient research depends on the available tools and applications.| Create openly available platforms, tools, and services for researchers.|
|Knowledge-creation could be more efficient if researchers worked together.|Foster a culture that supports opening up about the process of knowledge creation and provide tools that facilitate sharing.|
|Academic contributions today need alternative impact measurements.|Develop and implement an alternative metric system for research impact and academic success.|
|The access to knowledge should be equally distributed, but currently is not.|Generate new systems that ensure knowledge is freely available for everyone.|
|Research is publicly funded and needs to be made accessible to the public.|Develop ways of making research accessible for citizens and reward researchers invest time in thsi practice.|

You might think that these beliefs and goals sound great, but you're an early career researcher. You're worried about getting your next position, producing well-cited papers, securing grants, and making a name for yourself. You're not vane, you just know that academic job market is a bit of a jungle. So, here's another RDM secret. Researchers have studied publication dynamics and  there seems to be be significant evidence supporting the hypothesis that open access articles are cited more often than those published under more restricted conditions. To learn more, we highly recommend reading [McKiernan et al's 2016 paper](https://doi.org/10.7554/eLife.16800) discussing this issue.

If you intend to publish an open-access article at UNIVIE and do not have grant funding that covers OA publication fees, check out the [Open Access Office](https://openaccess.univie.ac.at/en/), which can provide funding for the publication fees and help guide you through the publication process.

Quiz
================
You guessed it! It's time for another quick quiz. This one covers the FAIR principles and Open Research. Each question has at least one correct answer, but there can also be multiple correct answers.

To ensure you data is as FAIR as possible, you should:

    [[ ]] Make your (non-sensitive) data available upon request.
    [[X]] Place your data in a trusted public respository.
    [[X]] Ensure your data is supported by rich metadata.
    [[X]] Use non-proprietary file formats whenever possible.
    [[ ]] Not apply a license to data so others can freely use it. 


Publishing papers in an open source format supports open science, but does little to benefit individual researchers. 

    [[ ]] True
    [[X]] False

### Comparison: RDM, FAIR, Open Research (Data)
We know we’ve thrown a lot of terms and concepts at you in this module: FAIR, Open Research, RDM, etc. We won’t make you read about it all again, but we do want to provide you with this handy summary table. It shows the similarities and differences between FAIR, Open Research, and RDM and emphasizes their relationship to one another. 

| FAIR Data Principles | Open Data | Research Data Management |
| -------- | -------- | -------- |
| Is about metadata and findability | Is available on the internet | Refers to the entire life cycle of research data from planning, generation, analysis, processing and backup, to documentation, archiving and publication, and finally, reuse by third parties |
| Is about standards and interoperability | Can be freely used, modified and shared by anyone for any purpose | Enables FAIR and Open Data |
| Is about machine-to-machine communication | Research data should be open as a default, unless there are legitimate reasons for keeping them closed. | RDM is mandatory in most funded projects that generate or reuse data |
| Is also applicable to senstive data| As a general rule, open access to other research outputs such as software, protocols, simulations, ELN and others is not required but strongly recommended | DMPs are planning instruments for your RDM |
| FAIR data is not equivalent to open data. Data can, and should be FAIR even when access is restricted.| Data can be open without being FAIR (e.g. missing metadata, propietary formarts, etc.)    |  RDM is an investment into your future    |

## Data Management Plans
Learning Objectives
======================

1. Define “data management plan (DMP)” and explain what types of information should be included in a DMP.
2. Explain why DMPs are helpful and how they can ensure research data is FAIR. 
3. Identify where help for generating DMPs can be found at the University of Vienna. 

### What is a Data Management Plan (DMP)?
The phrase "Data Management Plan” sounds hopelessly bureaucratic, but it actually describes a critical step in developing and implementing a research project. According to UNIVIE a DMP “describes how research data should be handled, and is therefore a tool for research data management. The plan explains which data are collected or generated during a research activity and specifies what needs to be done during the data lifecycle, i.e. the whole data process (storage, publication, citation, long-term availability, pseudonymisation, anonymisation, reuse, deletion, etc.).” 

Many funding agencies require that researchers create a DMP for projects, but DMPs make useful tools even if they are not requested by a granting agency. We’ll talk more about that later, but we should probably discuss what you include in a DMP first. If a funding agency requires that you create a DMP, they will probably have a template that you should use. This ensures that you supply the correct information in a format that program officers can quickly evaluate. The two most common templates in Austria are currently provided by the Österreichischer Wissenschaftsfonds FWF and by the European Research Council (ERC)/ Horizon Europe programs. Both templates cover similar information, but in a very different layout. The ERC/ Horizon Europe template asks researchers discuss how they will meet the requirements of each FAIR principle, while the FWF guides researchers through a series of step-by-step questions addressing practical issues related to data management and FAIR practices. 

We recommend looking at both templates to familiarize yourself. You can find them at the links below.
  
[ERC/Horizon Europe DMP Template](https://ec.europa.eu/research/participants/documents/downloadPublic?documentIds=080166e5dbb74f4a&appId=PPGMS)
[ERC/Horizon Europe DMP Manual](https://ec.europa.eu/research/participants/docs/h2020-funding-guide/cross-cutting-issues/open-access-data-management/data-management_en.htm)
[FWF DMP Template](https://www.fwf.ac.at/fileadmin/files/Dokumente/Open_Access/FWF_DMPTemplate_e.docx)

![Errant Scientist Data Management Plan Quality](https://scontent-vie1-1.xx.fbcdn.net/v/t31.18172-8/23916468_1990372521252055_5342830523000209050_o.png?_nc_cat=104&ccb=1-7&_nc_sid=7f8c78&_nc_ohc=urufjcz3HFgAX-ZDY77&_nc_ht=scontent-vie1-1.xx&oh=00_AfDgUFnrphg1o4cEFuUyfuLp9H9Jco3_pxZYYE73tygdcQ&oe=65DB1CA6 "[Quality of Data Management Plans Remains Variable by Errant Science](https://scontent-vie1-1.xx.fbcdn.net/v/t31.18172-8/23916468_1990372521252055_5342830523000209050_o.png?_nc_cat=104&ccb=1-7&_nc_sid=7f8c78&_nc_ohc=urufjcz3HFgAX-ZDY77&_nc_ht=scontent-vie1-1.xx&oh=00_AfDgUFnrphg1o4cEFuUyfuLp9H9Jco3_pxZYYE73tygdcQ&oe=65DB1CA6), [CC-BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)")

As we said above, if you are submitting a DMP to a granting agency you should use the template provided, but if no template is available or you are writing the DMP for your own reference, we highly recommend using the FWF materials to assist you. Overall, the FWF provides a thorough list of issues you should consider and gives a good list of practical questions to answer. 

Regardless of your DMP’s format, there are some topics you should always cover^1^.

* Provide basic administrative information about your project. 
* Describe the dataset that will be generated or any datasets that you are reusing.
* Describe your project’s metadata and methods of organizing and documenting data. 
* Explain how your data will be stored, backed-up, and preserved. 
* Note how your data will be licensed. 
* Discuss how and when your data will be published. 
* Outline any costs associated with managing your data. 
* Briefly explain any legal or ethical issues within your project and how you will address them. 
* Clarify who will have the right to use the generated data. 
* Illustrate which project will be responsible for each task outlined in the DMP. 

We'll work more on writing a good DMP during the in-person portion of this course and do some exercises that will get you on the right path, but before we move on let's make sure we codify how writing a DMP can help you. 

### How DMPs Help
Here's the deal. Nothing in your deep evolutionary past prepared you to be a great scientist. Being a good scientist requires long-term planning and organization and our brains are much more focused on the short-term payouts released by sugar, fat, salt, and TikTok, that fuel our inherent dopamine addiction. That’s why we have to formulate plans about making plans...draw-up plans...and follow the plan. 

![Planning by XKCD](https://imgs.xkcd.com/comics/planning.png "[Planning by XKCD](https://xkcd.com/2755), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

A lot of people will tell you that writing a DMP is a silly administrative task that slows down the pace of scientific discovery, but we find that it can actually save time and make researchers more confident about the progress of their projects. Sometimes writing a DMP is a bit like eating your green vegetables. You might now want to do it, but you know you should. Here are a few ways writing a DMP now can help you in the future. 

1. A DMP describes how you will organize and document your data from the start, so you don't lose important information or spend days reorganizing files at the end of the project. 
2. Having a data storage and back-up plan makes it more likely that your data will be safe and secure. No one wants to re-do experiments because a computer crashed.
3. Selecting potential repositories and publishing options forces you to assess if a portion of your budget will be needed to maintain and archive your data properly, so that you aren’t surprised later with unexpected costs.
4. Detailing usage rights, responsibilities, and licensing choices early helps to limit conflicts and disagreements between project members later in the project.

We know this might still feel overwhelming, but never fear! The RDM team is here! 

Getting Assistance with your DMP at UNIVIE 
--------------------
Still feel a little trepedation when faced with the thought of writing a DMP for your PhD project? Don't worry. That's normal. DMPs even scare the most seasoned senior professors. Trust us. We would know. With that said, there is no reason to be afraid. There are people at UNIVIE who are here to help you! 

If you are part of the Centre for Microbiology and Environmental Systems Science (CMESS) or the Faculty of Life Sciences, you can contact your data seward directly! 

At CMESS, Michael Feichtinger is the data steward and you can reach him at michael.feichtinger@univie.ac.at. 

Emliy Kate is the data steward for the Faculty of Life Sciences and you can email her at emliy.jean.kate@univie.ac.at. 

Alternatively, you can always reach the UNIVIE RDM team at rdm@univie.ac.at. They're available to anyone at the university and are always ready to help! No question too small! No mess too big!

Quiz
================
Alright, it's quiz time. Let's see what you learned about DMPs. Each question has at least one correct answer, but there can also be multiple correct answers.

You only need a DMP if your granting agency, doctoral school, or supervisor requires that you write one. 

    [[ ]] True
    [[X]] False
    
A DMP should:

    [[X]] Define researcher roles and responsibilities. 
    [[ ]] Include the specs of your research equipment. 
    [[X]] Explain how you will organize your data. 
    [[ ]] Outline potential titles for papers that will result from your project. 
    [[X]] Indicate how much data storage and archiving will cost. 

At UNIVIE, I can get help with my DMP by:

    [[X]] Contacting my faculty data steward.
    [[ ]] Sending up a flare. 
    [[ ]] Spinning in a circle three times while reciting an ancient incantation. 
    [[X]] Reaching out to the UNIVIE RDM team via their website.

## Organizing your Data
Whenever you do something in a laboratory, your work is always a part of a larger project. To make sure your work is not lost when you leave the lab, you need to organize and annotate your research data in such a way that your current and future colleagues can easily find and use them.

Learning Objectives
===================

1.	Explain the best practices for organizing and naming files and folders. 
2.	Demonstrate the differences between open and proprietary file formats and know when to opt for an open or a proprietary format. 	
3.	Know how to organize data tables in a clear and concise manner. 

### Managing Raw Data
Understanding the different stages of data, from raw to analyzed, is crucial for effective data management. Structuring your data according to these different stages could be useful to keep your data organized and easily accessible throughout the research process.

Raw Data
--------------------
Raw data is the original data that has not yet been processed or analyzed. It is unique and lossless, meaning it contains all the information collected by the instrument used to capture it. Raw data is typically in its original form, without any modifications, and may be in various formats, such as text, numerical, audio, or visual.

Processed Data
--------------------
Processed data has already undergone some form of intervention, such as normalization, removal of outliers, filling in missing data, or any other modification to make it easier to work with or more suitable for specific analysis purposes. Processed data is typically in a format that is easier to work with, analyze, and visualize.

Analyzed Data
--------------------
Analyzed data has already been processed, interpreted, and analyzed. This stage involves using statistical or other analytical techniques to extract insights or knowledge from the data. Analyzed data is often presented in the form of graphs, tables, or other visualizations that help to communicate the findings.

Best Practices for Managing Raw Data
--------------------
Raw data is unique and should be safeguarded to prevent loss. The following are some best practices for managing raw data:

1. **Archive raw data:** Raw data should be archived in an appropriate manner for long-term preservation. This ensures that the data remains accessible for future analysis or reference.
2. **Create a copy:** Create a copy of the raw data as a working copy for processing and analysis. This helps prevent overwriting the original data, which is essential for preserving the integrity of the data.
3. **Organize raw data:** Organize the raw data to make it easier to work with. This includes naming conventions, file formats, and folder structures.
4. **Secure raw data:** Raw data should be secured to prevent unauthorized access or modification. This may include password protection, encryption, or other security measures.


### File Naming
Well-structured file names allow for easier and more efficient retrieval, tracking, and sharing of data. Here are some guidelines for creating effective file names:

- **Give a unique name:** Each file should have a unique name that distinguishes it from other files.
- **Use elements essential to identify the file:** Include elements that are essential to identify the file, such as the name of the project, experiment, or subject.
- **Avoid long names, remove unnecessary elements:** Long file names can cause problems in storage, transfer, and handling of data. Keep file names concise and avoid unnecessary elements such as redundant information or irrelevant details.
- **Use ISO8601 standard for dates:** Using the ISO8601 standard for dates (i.e., YYYYMMDD) allows for consistent and chronological sorting of files.
- **Use ascending decimal version numbers:** When versioning files via filename, use ascending decimal version numbers (e.g., v1.0, v1.1, v1.2) to keep track of changes and updates.
- **Use alphanumerical characters only:** To ensure compatibility across platforms and systems, only use alphanumeric characters (A-Z, a-z, 0-9) in file names.
- **Do not use special characters:** Avoid using special characters in file names, as these can cause errors or conflicts in some systems.
- **Use underscores for separation:** Instead of using spaces in file names, use underscores ("_") for separation.
- **Do not alter or remove the extension of a file:** File extensions indicate the format and type of the file. Do not alter or remove the extension of a file, as this can cause errors or prevent the file from being recognized by certain programs or systems.
- **Be consistent and reach consensus:** It is essential to be consistent in how you build up names and ensure that there is consensus among all team/project members to avoid confusion and ensure understanding of naming conventions used for the project.
- **Document your naming scheme:** In order to ensure long-term success and facilitate comprehension of your consistent naming scheme, it is advisable to thoroughly document it. This documentation should be structured in a manner that enables people unfamiliar with your data to comprehend it easily.

### Folder Structure
A well-designed folder structure can help you quickly and easily locate the data you need, saving you time and effort. A clear and consistent folder structure can also help you collaborate effectively with other members of your research team. By establishing a standardized approach , everyone involved can easily access and understand your data.

- **Design clear folder structures that align with the project:** Before starting your research, plan out a folder structure that aligns with the objectives and goals of your project. This structure should be intuitive, easy to understand, and should follow a logical sequence of stages.
- **Use the same structure for different locations:** If you are working on the project across multiple computers or with different team members, ensure that the same folder structure is used across all locations.
- **Use max. 4 levels of folders:** Keep the folder structure as simple as possible by limiting the number of levels to a maximum of four. This will make it easier to navigate and manage.
- **Classify folders according to different project stages (raw, processed, analyzed):** Classify the folders based on the different stages of the project, such as raw data, processed data, and analyzed data. This will help you to organize the files based on their current stage of completion and make it easier to locate the data when needed.
- **Document the naming scheme and folder structure:** Once you have finalized the folder structure, document it clearly to avoid confusion and ensure that all team members are on the same page.


Quiz
================
Quiz time! Answer these questions about raw data and data organization. Each question has at least one correct answer, but there can also be multiple correct answers.

You should maintain an unedited copy of your raw data during your project.

    [[X]] True
    [[ ]] False

Processed data has been analyzed statistically and interpreted. 

    [[ ]] True
    [[X]] False

Which of the following are good tips for file naming and organzation? 

    [[ ]] Use spaces to seperate words and concepts within file names.
    [[X]] Balance the length of your file names with the need for critical information.
    [[X]] Create a document that records and explains your naming and organizational schemes. 
    [[ ]] Each project member should develop and organizational scheme that makes the most sense to them. 
    [[X]] Record dates in the YYYYMMDD format. 

### File Formats

A file format is a way of encoding information within a computer file. A program or application must be able to recognise the file format in order to access data within the file. Understanding file formats is not just a technical consideration; it is a critical aspect of ensuring the reproducibility and transparency of your research.

In general, we can distinguish between proprietary and open formats. Files in proprietary formats usually must be opened by the software in which they were created. Someone without a licence to the software may not be able to open the file at all. Open formats, in which the software company or collective publishes the format rather than keeps it proprietary, are more likely to be readable by more than one application. Adobe PDF is an example of an open format that may be viewed in a number of applications, not just Adobe products.
File formats that are non-proprietary (e.g. open source), or in widespread use, will tend to retain the best chance of being readable in the future. Proprietary formats, especially non-standard formats, used only by a specific software program or specific software version, are likely to present problems for future use. As you may have already surmised, archiving and publishing your data in the correct file format not only enhances their value but also promotes their FAIRness.^5^

Identifying File Formats
--------------------
A particular file format is often indicated as part of a file's name by a file name extension, or suffix. Conventionally, the extension follows a dot in the filename and contains three or four letters that identify the format (.jpg or .jpeg). In the Windows operating systems you can choose whether to display file suffixes or not. Mac files often do not have a suffix, which can be problematic when copying files to a different system to use.

As a general rule, it is advisable not to alter or remove file name extensions.

![One does not simply](https://i.imgflip.com/12bql0.jpg)

Text vs Binary Formats
--------------------
Text files are machine-readable through a character encoding standard such as ASCII or Unicode. Binary files can only be read by applicable software, and may be proprietary.

Some commonly used file extensions for saving plain text files include .txt, .csv, .html, .fastq and .tsv. The advantage of creating or saving research data in a text format, where possible, is that such files are 

- highly machine readable,
- tool-indepent,
- and still readable for humans in any plain text editor.
 
Therefore, text files are the most unlikely to become obsolete over time, and are a good format for sharing and long-term preservation.

Unfortunately, converting binary formats into text files sometimes leads to the loss of valuable metadata associated with your research data (e.g. transforming your microscopy data into TIFF files). Therefore, it is advisable to consider storing and archiving your data in multiple formats to ensure the preservation of comprehensive metadata.^5^

Criteria of Format Suitability
--------------------
In summary, to assess the suitability of your chosen formats you should consider the following three criteria:

- **Compatibility:** Compatibility ensures that your archived data can be readily accessed and utilized in the future, without dependencies on proprietary software or outdated technologies.
- **Loss-less conversion to alternative formats:** This criterion is essential for future-proofing your data, as technologies and standards may evolve over time and to maintain all the consisting data.
- **Suitability for long-term archiving:** Consider formats that offer stability, robustness, and wide acceptance within the scientific community.

To help you with your choice this table provides an overview on various format properties and their suitability:

| Suitability | Readability for Machines | Readability for Humans | Long-Term Stability|Metadata|
| -----------|---------------|-------|---------|----------
| Very good | Using **very prevailing** software | **Yes** and without special software | **Standard** format | **Completely** included|
| Good      |Using **prevailing** and **documented** software |   Compressed using standard procedure, but **uncompressed yes** | Already since long time or extensively **used** | **Technical** information included |
| Mediocre  |**Proprietary** standard format|Can be **converted** into readable format using standard software|Relatively **new** format|**Some** important information (e.g., units) included|
| Bad       |**In-house** reader software|**No**|Just **contrived** format|**None**|

Here are some recommended file format conversions you may consider:

- Convert text files, such as Word or PowerPoint, into unformatted text or PDF/A format.
- Convert tables stored in Excel files into CSV or TSV format.
- Convert pictures into TIFF, PNG, or JPEG format.^4^

As a general rule, it is important not to become overwhelmed by the task of selecting a proper file format. It's essential to remember that there may not always be a perfect solution for every type of data. Consider the formats and software you are currently using, evaluate whether it makes sense to save your work in an additional format, and determine if you can easily convert between working/sharing formats and archiving formats. By considering these factors, you can make an informed decision that balances practicality and the long-term preservation of your research data.

Quiz
================
It's time for a quiz about file formats! How exciting. Each question has at least one correct answer, but there can also be multiple correct answers.

_____ files are both machine and human readable, while _____ files are only machine readable. _____ files are the better option for storing reseach data.

    [[ ]] binomial; text; binary
    [[X]] text; binary; text
    [[ ]] binomial; text; text
    [[ ]] binary; text; text 
    [[ ]] text; binary; binary    
    
Using proprietary file formats that are common in your discipline is a best practice.

    [[ ]] true
    [[X]] false
    
When selecting file formats (for long-term archiving) you should consider: 

    [[X]] Machine readability
    [[X]] Long-term stability
    [[X]] Human readability
    [[ ]] University software availability
    [[X]] Metadata inclusion   

### Tables
Data tables play a crucial role in scientific research, as they provide (in the best case) a structured format for organizing and presenting data. But to make your data understandable for your future self, colleagues and possible re-users of your data, you should learn how to create tidy data and how to recognize and fix common problems of spreadsheets and data tables.

Tidy data refers to a structured and standardized format that follows a set of principles, allowing for ease of data manipulation and interpretation. Tidy datasets are organized in a way that each variable has its column, each observation has its row, and each value corresponds to a unique combination of variables and observations.

By adhering to some simple rules you could create **useful and tidy datasets** that

- Facilitate clear and unambiguous communication
- Are interoperable
- Are easy to harmonize, sort, aggregate, and parse
- Allow for the linking of source data and analyzed data
- Accompany (machine-readable) metadata  

For your success -- this already sounds like some bad advertisement -- you only have to follow some tipps and tricks for creation, formatting, standardization, validation and documentation of your spreadsheets and tables.
And remember, before you begin the process of transforming your raw data, it's essential to create a working copy specifically for the transformation.

Creation
--------------------
When creating your data tables you should keep in the mind the following key principles:

- **All data is labelled:** Each variable is clearly labeled in the header row, providing a descriptive name that represents the meaning of the data it contains.
- **Each subject has a unique ID:** Each subject or obversation has assigned a unique identifier. This identifier serves as a key to differentiate between individual observations and enables tracking and referencing specific data points.
- **Data is in rectangular format:** Information is organized in a rectangular structure, where each row represents a distinct observation, and each column represents a unique variable.
- **Keep data and metadata separate:** Accompanying notes, annotations, or metadata are kept seperate from your actual data. This separation ensures that the core dataset remains clean and uncluttered.
- **Do not encode information via color, font, etc.:** Conveying important information solely through visual attributes like color, font size, or formatting might improve your understanding, but introduces ambiguity and potential difficulties in the interpreation for other humans and machines.

Formatting
--------------------
You are able to represent data in a variety of ways but there are three interrelated rules which make a dataset tidy and easier to handle:

1. Each variable must have its own column.
2. Each observation must have its own row.
3. Each value must have its own cell.

![Following three rules makes a dataset tidy](https://d33wubrfki0l68.cloudfront.net/6f1ddb544fc5c69a2478e444ab8112fb0eea23f8/91adc/images/tidy-1.png "[Grolemund G & Wickham H (2017) R for Data Science](https://r4ds.had.co.nz/), [CC BY-NC-ND 3.0 US](https://creativecommons.org/licenses/by-nc-nd/3.0/us/)")

Standardization
--------------------
When working with tables, standardization plays a pivotal role in ensuring accuracy and coherence. **Consistency is key** and it starts with harmonious coding. Therefore, we recommend you to:

- Utilize three separate columns for year, month, and day, allowing for easy sorting and analysis.
- Adhere to a standard format across the table for time represenations.
- Apply abbreviations consistently and avoid variations.
- Use decimal notion in a uniform style to prevent discrepancies in numerical values. (Be aware that the German version of Excel uses comma as default decimal notion!)
- Clearly denote missing data instead of leaving cells empty.
- transform free text into categorical data to enable analysis and utilization in a more structured and quantitative manner.

Validation
--------------------
After creating, formatting and standardizing your data you should also validate them as quality control. This is in particular important if you are re-using data that you did not create on your own already following the above mentioned standards.

Data validation or cleaning involves checking if values fall within valid ranges and identifying any unexpected entries that may require further investigation. Additionally, it is important to eliminate leading or trailing spaces and other characters that could interfere with data analysis. The presence of outliers, missing data, or typos should be carefully examined to maintain data quality.

For small datasets you may still be able to check these things manually, but if you are dealing with larger amounts of (messy) data that you have to review or clean up before your analysis, you could automate this process by using for example Python, R, Excel, Google Sheets or OpenRefine. There a loads of guides and tutorials on the internet about this topic, but here are some sources you can use as a starting point:

[Pythonic Data Cleaning With pandas and NumPy](https://realpython.com/python-data-cleaning-numpy-pandas/)

[Cleaning Data in Excel (Youtube)](https://youtu.be/_jmiEGZ6PIY)

[Understanding Data Cleaning - Google Sheets (Youtube)](https://www.youtube.com/watch?v=kCP-H8VRDCw)

[OpenRefine](https://openrefine.org/)

Documentation
--------------------
Of course, your data needs to be properly documented. You will learn more about capturing the metadata of your data (and tables) and version control in the next section, but keep these three tips in mind for now:

- Create a README file.
- Use a proper file naming convention to accommodate multiple versions of your data files.
- Save your data in a machine-readable, text-based format such as .csv.^4^

Finally, all the effort pays off in the long-term. Not only will your data be more FAIR and re-useable by others, but once you have tidy data and the tidy tools provided by R packages in the tidyverse, you will spend much less time munging data from one representation to another. This will allow you to spend more time on the analytic questions at hand.
If you are not familiar with R or the **tidyr** package you should check out the amazing [R for Data Science](https://r4ds.hadley.nz/) (in particular the section 6 on Data tidying).

## Documenting and Annotating your Data

Learning Objectives
=======================

1. Summarize general considerations and solutions for your data documentation.
2. Demonstrate when and how to use README files and what they should include.
3. Know how to find appropriate standard metadata for datasets or samples. 
4. Summarize version control and the tools available for managing different versions of outputs. 
5. Explain how to document common scientific workflows and understand why documentation is important. 

### Data Documentation
Data documentation could be defined as the clear description of everything that a new “data user” or “your future-self” would need to know in order to find, understand, reproduce and reuse your data, independently. Data documentation should clearly describe how you generated or used the data, why, and where to find the related files. It could be used also as onboarding documentation for new colleagues, even if the responsible researcher leaves the project.

Due to the large variety of experiments, techniques and collaborative studies that usually occur within the same project, it is challenging to keep good documentation. However, lack of good data documentation often leads to data loss, not reproducible results and therefore, waste of money and time.

By the end of this section, you should be familiar with best-practices considering data documentation.

When documenting your data you should keep the following things in mind:

- Write the documentation in such a way that someone else who is known to the field cannot misinterpret any of the data. 
- Independently of the tools you will use, data documentation is needed at two levels: documentation about the entire study or project and documentation about individual records, observations or data points.

  - Study-level documentation describes the project title and summary, study aims, authors, institutions involved, funds, methods, licence and identifier for each dataset, folders structure, file naming conventions, versioning system, relation between files or tables and other general information.
  - Data-level documentation provides information about individual records or data point, such as the meaning of each variable name, label, ID or type (numeric, string, regular expression, date, etc.), units (i.e., cm, kg…), experimental factors, categories, controlled vocabulary or ontology terms accepted as values for each variable, missing values code and so on. An example could be a data file that contains a "sex" field: someone known to the field could try to misinterpret that from "external sex organs present at birth" to "chromosomal XX or XY" or "high or low testosterone level" or "social gender" or other. In order to avoid this, the way the assignment is made must be part of the documentation or of the data itself (controlled vocabulary).

- Both the study- and data-level documentation must be generated as early as possible in the research process and also maintained, in order to be accurate and complete
- Documentation is also required when publishing your data. General-purpose repositories usually require only study-level documentation, while discipline-specific repositories generally require both study-level and data-level documentation. Importantly, repositories often accept data and documentation in a very strict format: they can require a predefined set of attributes or fields (metadata checklists) to be filled, ontology terms to be used, specific (meta)data schemas to be adopted. We recommend familiarising yourself with  the requirements of the repositories that could be appropriate for publishing your data already at the beginning of the project, so that you can start documenting and formatting your data accordingly as early as possible.
- Make sure the documentation is kept close to the data, so that nobody will be exposed to the data without being able to find the documentation.
- It is best practice to use one appropriate tool or an integration of multiple tools for data documentation during a project. Suitable tools for data documentation are Electronic Lab Notebooks (ELNs) and/or Laboratory Information Management Systems (LIMS). UNIVIE does not currently have a preferred ELN or LIMS solution, but online platforms for collaborative research and file sharing services (such as [OSF](https://osf.io/)) could also be used as ELN or data management systems. For help making this decision, contact your data steward.
- For your data documentation files can be stored in several formats depending on the features available in your data documentation tool (if using one), your needs or skills. Machine-readable or -actionable formats are preferred to non-machine-readable ones. Also non-proprietary formats are preferred over proprietary ones.

When it comes to addressing issues in data documentation, there is no single optimal solution; instead, it exists as a spectrum ranging from inadequate to excellent documentation. Even something as basic as maintaining a digital record of your handwritten lab notebook or including a reference to it in a README file alongside your dataset can serve as an initial step.


### Metadata Standards

Highly structured data documentation is called **metadata**. Generating metadata in a machine-readable or -actionable format makes your data more FAIR . Metadata provides structured and searchable information so that a user can find existing data, evaluate its reusability and cite it.

It is good practice to use international standard metadata schemas to organise and store your (meta)data in a structured way. A metadata schema describes the relations, such as hierarchy, of the elements that belong to the structure. Most metadata schema are accompanied by a fixed set of attributes about the data that needs to be provided. Such metadata standards are community efforts and often under a constant development process. 

Metadata standards often depend on the use of **ontologies** and **controlled vocabularies**. An ontology is a formal representation of knowledge that defines concepts, their properties, and the relationships between them and establishes a hierarchical structure that organizes knowledge in a logical and systematic manner. Controlled vocabularies, on the other hand, consist of a predefined set of terms with specific meanings. They establish a controlled and standardized vocabulary for describing data elements, attributes, or concepts within a specific context. Used wisely, they can enable both humans and computers to understand your data. There is no clear-cut division between the terms "vocabulary" and "ontology", but the latter is more commonly used when dealing with complex (and perhaps more formal) collections of terms and relationships. Ontologies typically provide an identifier. 

The real challenge, however, is to decide on what metadata standards, ontologies and controlled vocabuleries you may want to or have to use for your data.

Finding Metadata Standards for your Datasets
--------------------

There are multiple standards for different types of data, ranging from generic dataset descriptions (e.g. DCAT, Dublin core, (bio)schema.org) to specific data types (e.g. MIABIS for biosamples).

You should decide at the beginning of the project what are the recommended repositories for your data types (you will learn more on repository choice in the following module). Some repositories require a specific metadata standard. We, therefore, recommend familiarising yourself with the requirements of the repositories that could be appropriate for publishing your data already at the beginning of the project, so that you can start documenting and formatting your data according to their requirements as early as possible.

If you have a repository in mind:

- Go to the repository website and check the “help”, "guide" or “how to submit” tab to find information about required metadata.
- On the repository website, go through the submission process (try to submit some dummy data) to identify metadata requirements. For instance, if you consider publishing your transcriptomic data in ArrayExpress, you can make your metadata spreadsheet by using [Annotare 2.0 submission tool](https://www.ebi.ac.uk/fg/annotare/), at the beginning of the project.
- Be aware that data type specific repositories usually have check-lists for metadata. For example, the European Nucleotide Archive provides [sample checklists](https://www.ebi.ac.uk/ena/browser/checklists) that can also be downloaded as a spreadsheet after log in.

If you do not know yet what repository you will use, look for what is the recommended minimal information (i.e. “Minimum Information ...your topic”, e.g. [MIAME](https://www.fged.org/projects/miame) or [MINSEQE](https://www.fged.org/projects/minseqe) or [MIAPPE](https://www.miappe.org)) required for your type of data in your community, or other metadata, at the following resources:

- [Research Data Alliance (RDA): Metadata Dictionary: Standards](https://rd-alliance.github.io/metadata-directory/standards/)
- [FAIRsharing.org](https://fairsharing.org) at “Standards” and “Collections”
- [The Digital Curation Centre (DCC): List of Metadata Standards](https://www.dcc.ac.uk/guidance/standards/metadata/list)

Please note that for certain data types, metadata standards may not be established by the research community. In such cases, README files are commonly used to describe the datasets (see below).^1^

Finding appropriate Vocabularies and/or Ontologies
--------------------

There are many vocabularies and ontologies available on the web. Finding a suitable one can be difficult and time-consuming.

Similarly to the metadata standards, check whether you really need to find a suitable ontology or vocabulary yourself. Perhaps the repository where you are about to submit your data have recommendations? Or the journal where you plan to publish your results? You also have to consider your goal with sharing data. Which formal requirements (by e.g. by funder or publisher) need to be fulfilled? Which parts of your data would benefit the most from adopting ontologies?

After taking these considerations into account and deciding to adopt specific ontologies or vocabularies for your data, there are several factors you should consider:

- Learn the basics about ontologies. This will be helpful when you search for terms in ontologies and want to understand how terms are related to one another.
- Define a list of terms that you want to find ontologies for. Include in the list also any alternative term names that you are aware of.
- Search for your listed terms on dedicated web portals. These are a few:

  - [Linked Open Vocabularies (LOV)](https://lov.linkeddata.es/dataset/lov/)
  - [EMBL-EBI Ontology Lookup Service](https://www.ebi.ac.uk/ols/index)
  - [Ontobee](http://www.ontobee.org)
  - [BioPortal](https://bioportal.bioontology.org)
  - [AgroPortal](https://agroportal.lirmm.fr)
- Accept that one ontology may not be sufficient to describe your data. It is very common that you have to combine terms from more than one ontology.
- Accept terms that are good enough. Sometimes you you cannot find a term that perfectly match what you want to express. Choosing the best available term is often better than not choosing a term at all. Note that the same concept may also be present in multiple ontologies.^1^

### README files

README text files are often the simplest and most effective way to document your data, particularly when there are no established metadata standards. They serve as valuable documentation, making your data more understandable and reusable. README files can be used to include notes on the organization and content of digital folders and files. In the following paragraphs, you will discover best practices for creating README files and incorporating them as study- and data-level documentation.

When creating your README files follow these best practices:

- Create READMEs for logical clusters: The amount and scope of your clusters depends on the size and complexity of your data. Each cluster should have its own readme file, providing an overview and details specific to that cluster. You should at least haveone README file describing your project and one for your raw data.
- Name the README properly: Give your README file a clear and descriptive name that reflects its content and purpose.
- Write your readme as a plain text file and avoid propriertary formats.
- Format multiple readme files identically to enhance readbility and reduce confusion when you or others navigate through your different datasets. Remember to use standard formats, such as YYYY-MM-DD for dates, to promote interoperability and ease of understanding.
- Follow your discipline’s conventions for units, names, and keywords.

You can strategically plan the level of detail in your README files to ensure it is realistically manageable for you, while also providing sufficient information for someone who encounters your data for the first time to understand it.

Project-Level README
--------------------
Your project-level README should include the following information:

- Project title and a concise project description explaining the purpose of data collection.
- Creator's name and contact information for potential inquiries or collaborations.
- Details about the project's funding, including the funding agency and grant number associated with the project.
- Titles of the datasets used or generated by the project.
- Information regarding data confidentiality, access restrictions, and conditions of use.
- A comprehensive list of publications that cite or utilize the data from this project.
- Description of the file structure and organization, including folder hierarchies, naming conventions, file formats, and the relationships between different datasets.

Such well-structured project-level README that encompasses the aforementioned information will facilitate understanding, collaboration, and reproducibility of your project.

Here is an example how such README file could look like:

![README File Example1](https://raw.githubusercontent.com/feichtingerm/rdmlifesciunivie/main/images/projectlevelreadme_example.png)
![README File Example2](https://raw.githubusercontent.com/feichtingerm/rdmlifesciunivie/main/images/filetree_example.png " [README File Examples](https://zenodo.org/record/7573695/files/3-2_Espresso_READMEs.pdf?download=1), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode) ")

Please keep in mind that the provided format may not be optimized for machine-readability when compared to formats such as JSON files.


Data-Level README
--------------------
Your data-level README should encompass the following information:

- Title and a concise description of the dataset.
- Methodological details, including instrument- or software-specific information, standards, calibration information, and environmental or experimental conditions.
- Validation and quality assurance procedures employed during data collection.
- Data processing steps undertaken and any resulting alterations made to the data.
- A comprehensive variable list, including complete names and definitions of tabular data.
- Units of measurement for each variable.
- Abbreviations or acronyms used throughout the dataset.
- Codes used to indicate missing or invalid data.
- Reference to the project-level README for additional context and information.

By including these elements in your data-level README, you ensure that users have the necessary information to understand, analyze, and interpret the dataset accurately.You can access a comprehensive data-level README template provided by Cornell University [here](https://cornell.app.box.com/v/ReadmeTemplate). 

In conclusion, the richness and structure of README files add significant value to your data, providing understanding and reusability. However, it is essential to **strike a practical balance in the level of detail to ensure manageability for yourself**.

### Version Control

Version control is a way to keep track of changes made to files and datasets. While the implementation of a good file naming convention will indicate that different versions exist, this will not explain the difference between two (or more) versions. File versioning will enable transparency about which actions and changes were made and when. This makes it easy to backtrack and find something that was present in a previous version, but was later deleted or changed.

When considering which method of version control to employ, you may want to ask yourself the following questions:

- Do I need to collaborate on files, perhaps at the same time?
- Is there a need to be able to backtrack and restore a previous version?
- Will there be many changes made?

For smaller demands of versioning, manual management can be sufficient. This can be done by keeping a log where changes for each respective file are documented, version by version or even descriptive file names.

Many cloud storage services, like u:cloud and OneDrive, provide automatic file versioning, which can be convenient for spreadsheets, text files, and slides.

For more advanced version control, conflict resolution, and back-tracing capabilities, it is recommended to use dedicated version control software such as Git. Git can be hosted on platforms like GitHub and GitLab. It is primarily designed for managing source code files. But you could use it for anything text based. It's important to note that large binary files (e.g., videos, large images) may not be suitable for Git repositories due to their size, as they can bloat the repository and slow down operations. 
While operating Git through the command line may initially seem daunting, there are plenty of short tutorials available online that can help you use it with ease.


### Workflows

In addition to version control and manual management, there are cases where using workflow tools can be highly beneficial. Workflow management systems help organize and automate the execution of computational tools. Compared to standalone scripts, workflow systems provide advantages such as documentation of computational analyses, scalability (including cloud execution), and improved reproducibility.

Workflow tools enable the specification of software packages or containers for the tools used within the workflow. This allows others to easily rerun the workflow without the need to pre-install every required software component, enhancing reproducibility. The field of workflow management is thriving, and [numerous workflow management systems](https://s.apache.org/existing-workflow-systems) are available.
Among the many workflow management systems available, one can mention:

- Workflow platforms that manage your data and provide an interface (web, GUI, APIs) to run complex pipelines and review their results, such as [Galaxy](https://galaxyproject.org/).
- Workflow runners that take a workflow written in a proprietary or standardized format and execute it locally or on a remote compute infrastructure, such as [Nextflow](https://www.nextflow.io/) or [Snakemake](https://snakemake.readthedocs.io/).
    - If you are planning to use Snakemake on the [Life Science Compute Cluster](https://lisc.univie.ac.at/) (LiSC) there is a page in the [LiSC Wiki](https://lisc.univie.ac.at/wiki/content/working_environment/applications/snakemake) that provides support (access requires a user account).

Additionally, existing workflows can be reused or shared on popular services like [WorkflowHub](https://workflowhub.eu/) and [Dockstore](https://dockstore.org/), which provide repositories for workflows, making them accessible to the wider community.^1^


![XKCD Data Pipeline](https://imgs.xkcd.com/comics/data_pipeline.png "[Data Pipeline by XKCD](https://xkcd.com/2054), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

### Quiz

What a surprise, another quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

Your data documentation should, at least, include documentation on:

    [[X]] Study-level
    [[ ]] Folder-level
    [[ ]] File-level
    [[X]] Data-level
    
Metadata standards, ontologies and controlled vocabularies:

    [[ ]] Should never be used together.
    [[X]] Can enable both humans and computers to understand your data.
    [[X]] Describe your data.
    [[ ]] Require hardly any effort to be established.
    [[X]] Can be required for specific repositories.
    
A README file describing one of your datasets should contain:

    [[X]] Methodological details.
    [[X]] Validation and quality assurance procedures.
    [[X]] Data processing steps.
    [[ ]] A definition of the FAIR principles.
    [[X]] units of measurement for each variable.
    [[ ]] As much information as possible.

Which statements on version control are correct:

    [[ ]] You should always use Git for any form of version control.
    [[X]] Descriptive file names can be used as version control.
    [[X]] Cloud storage services often provide automatic file versioning.
    [[X]] File versioning is particulary useful when working collaboratively.


## Storing and Securing your Data
Learning Objectives
=========================

1. Summarize the best practices for data storage and back-up. 
2. Know what storage resources are available to you at the University of Vienna.

### Best Practices for Storage and Back-up

The need for data storage arises early on in a research project, as you will need a space to place your newly created data. Therefore, it’s always a good practice to think about storage solutions during the project’s planning phase, request storage in advance, and ensure funds are available to pay for it^1^. 

The storage solution for your data should fulfill certain criteria (e.g. space, access & transfer speed, duration of storage, etc.), which should be discussed with an IT specialist or a member of a RDM team. You may choose a tiered storage system for assigning data to various types of storage spaces based on requirements for access, performance, recovery and cost. Using tiered storage allows you to classify data according to levels of importance and assign it to the appropriate storage tiers or move it to different tier. For example, once analysis is completed you might move data to lower tier for preservation or archiving^1^.

Tiered storage is usually classified as either “cold” or “hot” storage. Hot storage is associated with fast access speed, high access frequency, high value data that is stored on faster drives such as solid-state drives (SSD). This storage is usually located physically near the user (like on campus) and incurs higher costs. Cold storage is associate with low access speed and frequency and consists of slower drives or tapes. This data is usually stored in a more distant location and incurs lower costs^1^.

When looking for solutions to store your data during the collection or generation phase, you should consider the following aspects^1^.

* The volume of your data is an important discerning factor to determine the appropriate storage solution. At the minimum, try to estimate the volume of raw data that you are going to generate or collect.
* Know what kind of access/transfer speed and access frequency will be required for your data.
* Considering where the data will come from is also crucial. If the data comes from an external facility or needs to be transferred to a different server, you should think about an appropriate data transfer method.
* It's a good practice to have a copy of the original raw data in a separate location, to keep it untouched and unchanged (not editable).
* Know for how long the raw data, as well as data processing pipelines and analysis workflows need to be stored, especially after the end of the project. 
* Make sure to keep metadata together with the data or establish a clear link between data and metadata files.
* In addition to the original “read-only” raw (meta)data files, you need storage for files used for data processing and analysis, as well as the workflows/processes used to produce the data. 
* Consider who is allowed to access the data (in case of collaborative projects), how do they expect to access the data during the project. 
* Finally, consider any legal or ethical concerns. Sensitive data will require special storage conditions and your funding source, institute, or country may have legal limitations regarding how data is shared. 

If you are not working with sensitive data, a good rule for backing-up your files is the 3-2-1 concept. This rule states that there should be three copies of your files. These copies should be stored on at least two different storage mediums, like a personal computer, external hard drive, server, or cloud drive. One of these back-ups should be in a different physical location than the other two. Today, this often means that your data is back-up to a server outside of your univeristy building via a cloud service and your files are also saved to your computer and something like an external hard drive. 

It is recommended to utilize automatic backup systems whenever possible. One option is to use a software client on your PC that automatically syncs your data with the cloud, such as OneDrive or u:cloud (see more details below).

If you store your data on the institutional Share, your data is backed up once a day. You can restore deleted data, folders, and older versions of data. For data and folders up to 5 days old, you can perform the restoration yourself. However, for data and folders older than 5 days, please contact the ZID Helpdesk for assistance.

When working on the [Life Science Compute Cluster](https://lisc.univie.ac.at/) (LiSC), please note that only data in your `/home` and `/archive` are daily backed up to tape. The backup system retains 3 versions of each file and keeps inactive (deleted) files for 6 months. Data stored on `/scratch` has **no** backup. Only use it for everything intermediate that can be reproduced from your project data and scripts. You can find more information on the LiSC storage policy in the [LiSC Wiki](https://lisc.univie.ac.at/wiki/content/working_environment/storage_policy) (access requires a user account).

As we mentioned above, the rules for sensitive data are more complex and your should talk to a RDM specialist before you select storage solutions for information concerning living people. Additionally, it quickly can become problematic to store large datasets (>100 GB) using the 3-2-1 rule and shifts in planning often need to be made. 

### Storage Solutions at UNIVIE
Hopefully this hasn't made you feel too overwhelmed. Remember that RDM help at UNIVIE is always available. Furthermore, the university has several in-house storage options you can use, but keep in mind that some of these solutions do have associated fees.

|Service | Function | Storage Space | Collaboration Features|Cost|Availability|
| -----------|---------------|-------|---------|----------| -----------
|[Personal Online Storage Space (Z:Drive)](https://zid.univie.ac.at/en/online-storage-space/) | Personal file storage | 10 GB; Expandable with justification |None |Free|Immediate|
|[Share](https://zid.univie.ac.at/en/share/) | File storage and sharing; Managed through organizational unit| Ulimited |Between employees and students; Extended u:account available for guests  |EUR 0.03 per GB/year|Request Required|
|[u:cloud](https://zid.univie.ac.at/en/ucloud/) | Personal file storage and sharing| 50 GB  |Between employees and students; Extended u:account available for guests  |Free|Immediate|
|[u:cloud pro](https://zid.univie.ac.at/en/ucloud-pro/)| File storage and sharing; For projects or teams| 250 GB; expandable with justification  |Between employees and students; Outside users can upload and download  |EUR 0.03 per GB/year|Request Required|
|[One Drive by Microsoft 365](https://zid.univie.ac.at/en/microsoft-365/)| File storage and sharing| 50 GB|Internal and external sharing; Non-university users can edit files|Comes together with MS365 license for university employees|Immediate|
|[Gitlab*](https://zid.univie.ac.at/en/gitlab/)| Storing code; Version control| Unlimited; Code and supporting documentation|	Permissions and licensing options available|Free|Request Required|
|[Central Backup](https://zid.univie.ac.at/en/central-backup/)| For files not otherwised backed-up; Requires some user maintenance| Unlimited|None|Free|Request Required|

*At UNIVIE you are welcome to set-up your own Github or Gitlab account. 

### UNIVIE Tools for Collaborative Work 
At some point during your time at UNIVIE you will probably need to work on a project with other people. While u:cloud does have come collaboration features, we find the resources provided by Microsoft 365 to be the most intuitive and easiest to use with people outside the UNIVIE network. With this said, keep in mind that sensitive data should never be stored on Microsoft One Drive.

Github and Gitlab continue to be excellent choices for code collaboration. The LiSC operates a Gitlab virtual machine for their users as well, and you can obtain Gitlab access by contacting their [helpdesk](https://lisc.univie.ac.at/helpdesk).

Finally, if you need to send large files (up to 250 GB in size) to a collaborator, you can use [Aconet File Sender](https://zid.univie.ac.at/en/filesender/). 
If you are working on the LiSC and need to share data with external parties, you can utilize the `/fileshare` directory. For further details, please refer to the [LiSC Wiki](https://lisc.univie.ac.at/wiki/content/working_environment/fileshare) (access requires a user account) or reach out to the [LiSC helpdesk](https://lisc.univie.ac.at/helpdesk) for assistance. 

### A Note on Basic Security and Working with Sensitive Data 
We aren't going to go too deep into cyber security, but we wanted to pass on few tips that will help keep your data safe and secure: 
Create Strong Passwords: Avoid easily guessable information. Include upper case and lower case letters, special characters, and numbers in your passwords. Consider storing your passwords using an encrypted password storage application. 

* **Use Two-Factor Authentication**: When available, opt into two-factor authentication. 
* **Secure your Office**: Don't make it easy for bad guys to steal your shiny stuff. 
* **Lock your Devices**: When you leave your office, always lock your computer. Also enable biometric log-in or passcode log-in for your tables and cell phone. 
* **Remember to Update**: Keep your software and operating system up-to-date. Updates often include security patches. 
* **Be Cautious**: Be skeptical of emails from unknown senders, especially those who ask for your personal information. Do not click links or open attachments in suspicious emails.
* **Report Suspicious Activity**: You can forward suspicious emails as attached EML files to the ZID IT security team for analysis at security.zid@univie.ac.at.

We'll talk more about sensitive data below, but if you are planning a project that will use sensitive information, please contact the UNIVIE RDM team for help with data storage, back-up, and protection. 

If you are part of a project using sensitive data, keep these best practices in mind: 

* **Encryption**: Only store sensitive data on devices with full disk encryption.
* **Limit Copies**: Limit the copying of sensitive data. If you must copy sensitive data, always encrypt it. 
* **Be Mindful of Back-Ups**: Ensure all back ups, even those on the cloud, are encrypted.
* **Avoid Transport**: Even encrypted sensitive data should only leave your workspace when absolutely necessary. 
* **Be Cautious of Transfers**: Do not transfer un-encrypted sensitive data over the internet. 
* **Data Disposal**: Delete sensitive data when no longer needed. Use a digital file shredder to ensure data cannot be restored. Always empty your computer's trash bin. 

### Quiz

Yipee! Quiz time!  Each question has at least one correct answer, but there can also be multiple correct answers.

For datasets that are neither sensitive nor gigantic, how many copies of the file should exist? 

    [[ ]] 2
    [[X]] 3
    [[ ]] 4
    [[ ]] 5    

When making plans for storing your data during a project, what are some things you should consider? 

    [[ ]] If your metadata is publically available.
    [[X]] How long your files need to be stored.
    [[ ]] Who will require access to the data.
    [[ ]] The volume of your data.
    [[ ]] How often you will need to access the files.     

All UNIVIE storage options are free for students and employees. 

    [[ ]] true
    [[X]] false  
    
All UNIVIE storage options are suitable for sensitive data. 

    [[ ]] true
    [[X]] false    

## Publishing and Preserving your Data

Learning Objectives
======================

1. Explain what data and information should be preserved and why data should be preserved. 
2. Know how to select data repositories. 
3. Explain different types of persistent identifiers and understand their importance. 
4. Explain the importance of assigning a license to scientific outputs and understand the differences between the most common licenses. 

### Data Preservation

Data preservation consists of a series of activities necessary to ensure safety, integrity and accessibility of data for as long as necessary, even decades. **Data preservation is indeed more than just data storage and backup**, since data can be stored and backed up without being preserved. Data preservation prevents data from becoming unavailable and unusable over time through appropriate steps:

- Ensure data safety and integrity.
- Change the file format (format migration) and update software to make sure that they do not become outdated or obsolete.
- Change hardware and other storage media (such as paper, magnetic tape, etc.) to avoid degradation.
- Ensure that data is organised and described with appropriate metadata and documentation to be always understandable and reusable.

There are several important reasons to preserve research data:

- Guarantee that your data can be verified and reproduced for several years after the end of the project.
- Allow the reuse of the data in the future for different purposes, such as teaching or further research.
- Funders, publishers, institutions and organisations could require a specific period for preservation of certain data for a specific purpose.

    - The [UNIVIE RDM policy](https://rdm.univie.ac.at/rdm-policy-and-faq/) emphasizes that researchers have the discretion to decide whether and what type of data they preserve, as long as they comply with funder guidelines or journal requirements. However, the policy strongly encourages researchers to engage in data preservation practices.
- Preserve data that have significant value for an organisation, a Nation, the environment or  for the entire society.^1^

![XKCD Digital Resource Lifespan](https://imgs.xkcd.com/comics/digital_resource_lifespan.png "[Digital Resource Lifespan by XKCD](https://xkcd.com/1909), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/legalcode0)")

Deciding on Which Data to Preserve
--------------------

Not all data should be preserved. It is important to carefully select which data to preserve, considering the associated effort and costs. Typically, all data underlying your publications should be preserved. Although journal requirements may not be overly strict at present, reputable journals increasingly demand publication and preservation of all underlying data in suitable repositories. Within Horizon Europe projects, it is mandatory to deposit all generated data into trusted repositories. The data should be made openly accessible (if possible) as early as possible. It's recommended to deposit (meta)data as soon as possible after production/generation or after processing and quality controls.
Therefore, it becomes evident that data preservation will play a pivotal role in shaping the trajectory of your future research career.


Common criteria to select the data to preserve for a certain amount of time are:

- data required to be preserved by funder, publisher and institution policies (usually, data should be preserved for at least 5 to 10 years after the end of the project)
- data preservation of which is needed by legal or ethical requirements (e.g. clinical trial data)
- unique data or that cannot be easily re-generated (e.g. raw data, analysis workflow)
- data that will probably being reused in the future
- data of great value for society (scientifically, historically or culturally)^1^


When preparing data for preservation several requirements need to be fulfilled:

- Do not include data that are temporary or mutable.
- Ensure well described and self-explanatory documentation.
- Include information about provenance.
- Include sufficient licensing information.
- Ensure that data is well organised.
- Ensure that a consistent naming convention is used.
- Use standard, open source, file formats instead of proprietary ones.^1^

If you need to preserve non-digital data (e.g. paper), consider whether digitalising the data is feasible or consult your data stewards for support.

If you need to preserve materials, such as micro-organisms, biomaterials or biomolecules, you have to find appropriate centers or biobanks. Your supervisor should be able to provide you with guidance on that.

Once you have determined which data you intend to preserve, the next step is to select a suitable repository, choose an appropriate license, and ensure that your data is assigned a persistent identifier (PID) to ensure proper citation. Further details on these aspects will be covered in the upcoming section.


### Choosing a Repository

A **trusted repository** refers to a reliable and recognized digital platform or service that is dedicated to the long-term preservation, management, and accessibility of your data. It adheres to established standards and best practices for data curation, ensuring the integrity, authenticity, and security of the stored data. 
The choice of the most suitable repository for your data strongly relies on the type of data you have. It can be challenging to determine the ideal repository if specific guidelines are not explicitly provided by your funding agency or journal requirements.

If a discipline-specific repository, recognised by the research community, exists this should be your first choice since discipline-specific repositories often increases the FAIRness of the data. There exist a variety of tools and search engines that can help you on deciding on the best repository for your data:

- The [EMBL-EBI's data submission wizard](https://www.ebi.ac.uk/submission/) can help you choose a suitable repository based on your data type.
- Lists of discipline-specific, community-recognised repositories e.g.: [ELIXIR Deposition Databases](https://elixir-europe.org/platforms/data/elixir-deposition-databases) or [Scientific Data journal's recommended repositories](https://www.nature.com/sdata/policies/repositories)
- [re3data.org](https://www.re3data.org) and [FAIRsharing](https://fairsharing.org) websites gather features of repositories, which you can filter by discipline, data type, taxonomy and many other features.

    - When it comes to the FWF (Austrian Science Fund), it is crucial to mention repositories for data deposition in your DMP that are listed in [re3data.org](https://www.re3data.org).

If you are lucky and a discipline-specific repository is already established, they generally have information about data formats, metadata requirements and how data can be uploaded under a section called “submit”, “submit data”, “for submitters” or something similar. Read this section in detail. As already mentioned in previous modules, it's good to already get familiar with these requirements in the beginning of your research project so you can structure your data accordingly.

If you can't find a discipline specific repository, you have to use a general-purpose or institutional repositories. 

The UNIVIE operates [PHAIDRA](https://phaidra.univie.ac.at/) as an institutional repository that allows you to deposit any data there. If you wish to familiarize yourself with the user interface of PHAIDRA, a test instance of PHAIDRA is available within the university's network. You can access it [here](https://phaidra-sandbox.univie.ac.at/). It is worth noting that once you upload data to PHAIDRA, they cannot be deleted. Hence, the PHAIDRA Sandbox serves as an excellent tool for experimentation and trying out different features. Please be aware that access to your data and the ability to modify metadata on PHAIDRA (if they are not openly available) are linked to your UNIVIE account. Requesting access after leaving the university is possible but may require additional effort.

If you choose to use a general repository, we highly recommend utilizing [Zenodo](https://zenodo.org/). Zenodo is supported by CERN, OpenAIRE, and the EU, and actively promotes the Open Science movement. While alternative options like [Dryad](https://datadryad.org/stash) or [figshare](https://figshare.com/) exist, it's important to note that they either require payment for data submission or are affiliated with large publishers. For your submission to Zenodo, the [FAIR Cookbook](https://faircookbook.elixir-europe.org/content/home.html) provides a good step-by-step guide [here](https://faircookbook.elixir-europe.org/content/recipes/findability/zenodo-deposition.html).

If you need support with your submission to a specific repository or help on choosing the right one, you are always welcome to contact your data stewards or the UNIVIE RDM support.

![Repositree](https://errantscience.com/wp-content/uploads/Reposi-tree-copy.jpg "[Reposi-tree by Errant Science](https://errantscience.com/), [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)")

### Persistent Identifiers

The next step on the list to sustainable and FAIR publishing of your data is providing them with a persistent identifier (PID). A PID is a long-lasting reference to a resource. That resource might be a publication, dataset or person (e.g. [ORCID](https://orcid.org/)). Equally it could be a scientific sample, funding body, a research institution (e.g. [ROR](https://ror.org/)) or piece of software. Whatever it is, the primary purpose of the PID is to provide the information required to reliably identify, verify and locate it. This means that any dataset with a PID will be findable even if the location of the dataset and its web address (URL) changes. The central registry that manage PID will ensure that the given PID will point you to the digital resource’s current location.

There are different ways to obtain a globally unique persistent identifier, and you need to decide which one is the best solution for your dataset or resource.

- By publishing into an existing public repository. For most types of data, this is usually the best option because the repository will assign a globally unique persistent identifier or an accession number.
- By opening up your local database to the public. This requires that the resource has a sustainability plan, as well as policies for versioning and naming of identifiers. While this option could be a viable solution if there is no public repository that allows for the right level of exposure of your data, it puts a lot of responsibility on your shoulders for future maintenance and availability.^1^

As you may have guessed, in most cases, the repository where you upload your data will provide the identifiers for your data. Therefore, it is essential to choose a repository that offers persistent identifiers (PIDs). Additionally, if you haven't obtained an ORCID iD yet, now is an opportune time to [register](https://orcid.org/register) one. Having an ORCID iD ensures proper recognition for all your contributions and enhances your visibility as a researcher.

### Licenses

Assigning a license to your scientific outputs is important as it establishes the legal framework for the permitted (re)use, sharing, and dissemination of your research outputs. What licence you should apply to your research data depends on what rights protect your research data. Which licence to choose might be governed by funders’ mandates or legal contracts. Research data can have varying degrees of publicity. There are circumstances in which data may be subject to restrictions eg. if datasets contain sensitive information. 
As a general rule, it is advisable to choose and apply the least restrictive license whenever possible. This approach ensures the widest possible reuse of your scientific outputs. In most repositories you have to assign a license to anything you upload there. If you are sharing code in a GitLab or GitHub repository, you have the option to either assign a license during the creation of the repository or add one later.

[Creative Commons licenses](https://creativecommons.org/licenses/) are the best known open data licences and are available in human-readable and machine-readable forms, with different levels of permissions. [Creative Commons License Chooser](https://creativecommons.org/choose/) helps you choose the right Creative Commons licence for your needs and the [video tutorial from Kingsborough E-Learning](https://www.youtube.com/watch?v=5QxkuuiZwRU) shows how to add a Creative Commons licence to your work in practice.

You have to be aware that Creative Commons licenses are not suitable for software output. The following sources helps you find the right licence for your software and data:

- [EUDAT licence selector wizard](https://ufal.github.io/public-license-selector/).
- [Choose a license](https://choosealicense.com) is an online guide provided by GitHub to help you choose a license for open-source projects.

If your research data can be shared openly, consider putting it in the public domain by using the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license that requires attribution or even [CC0](https://creativecommons.org/share-your-work/public-domain/cc0). CC0 let you waive all your rights to the work ("No Rights Reserved").^1^


If you are not obligated by your funder or any other legal contracts to use a specific license, the [UNIVIE RDM Policy](https://rdm.univie.ac.at/rdm-policy-and-faq/) endorses publication of research data under open licences, provided no legal, contractual, ethical or other documented reasons prohibit it.

### Quiz

You learned how to preserve and publish your data and all you get is another stupid quiz. Each question has at least one correct answer, but there can also be multiple correct answers.

All your data should be preserved for at least 5 to 10 years. 

    [[ ]] True
    [[X]] False

When choosing a repository:

    [[X]] You try to find a discipline-specific repository.
    [[X]] You check publications in your field to see which repositories are used by the community.
    [[ ]] You avoid repositories that use metadata standards.
    [[X]] You look for a repository that provides PIDs.
    
Which licenses make your data or software openly available and allows others to adapt them for their use? 

    [[X]] CC0
    [[X]] GNU General Public License 
    [[X]] CC BY
    [[ ]] CC BY-NC-ND
    

## Ethical and Legal Aspects of RDM
Here's the deal. Issues related to research ethics and legal questions are a massive topic and we can't cover everything during this course. Frankly, we wouldn't even be qualified to do that.What we want to do here is draw you attention to a few topics, so that you are aware of them. By the end of this section, we hope you will have a developed a sense for when your project may involve legal or ethical issues, so that you can ask questions and get the help you need. 

Learning Objectives 
=======================

1. Develop a sense for when your project involves legal or ethical issues that require consideration.
2. Understand the difference between Responsible Research and Innovation (RRI)and Research Integrity. 
3. Know where you can find help with legal and ethical questions at UNIVIE.

### Responsible Research and Innovation (RRI) and Research Ethics

Let’s talk about the difference between Responsible Research and Innovation (RRI) and Research Ethics. According to the European Union’s Horizon 2020 research program, RRI is defined as “an approach that anticipates and assesses potential implications and societal expectations with regard to research and innovation, with the aim to foster the design of inclusive and sustainable research and innovation” (European Commission, n.d.). There are two aspects of this definition worth focusing on for the purpose of this introductory section. First, RRI refers to “potential implications and societal expectations.” Second, it’s about “the design of inclusive and sustainable research”. These are two traditionally important aspects of the ethics of science: how research is set up or designed, and what societal consequences this setup has. What is important here is that we consider these aspects of research when speaking of making it ethical.^3^

In contrast, Research Integrity refers to an “active adherence to the ethical principles and professional standards essential for the responsible practice of research” [(Korenman 2006)](https://ori.hhs.gov/education/products/ucla/default.htm). What this term brings into the discussion about research ethics are “professional standards” and “responsible practice”. Unlike in RRI, the question is no longer on the ethics of scientific output and its consequences, but on the ethics of how scientists conduct themselves in practice. Research integrity, in a sense, captures the ethics of the work done “behind the scenes”, outside the view of the general public^3^.

RRI and research integrity are by no means entirely distinct, as they can overlap in important ways. However, three differences between the concepts are outlined below. 
First, we can see that who is most impacted by the ethical questions differs in each case. RRI can be understood as outward-looking and focused on public perception and impact. In contrast, research integrity refers to how research findings are produced — it is inward-looking. A common term to describe a lack of research integrity is “research misconduct”^3^, which can include things like data fabrication or plagiarism. 

Second, RRI and research integrity each refers to a different type of scientific interaction. On the one hand, RRI questions how scientists engage with research subjects, or the public. One (in)famous case in which there was no respect for data subjects was the Tuskagee experiments, wherein African-American men were recruited to study the development of untreated syphilis. Volunteers were falsely told they were receiving free treatment and the monitoring and lies persisted for forty years [(CDC 2021)](https://www.cdc.gov/tuskegee/timeline.htm). On the other hand, Research integrity refers to how scientists engage with fellow researchers.^3^ 

Third, RRI and research integrity can address how the scientific process is impacted by societal (RRI) or institutional (research ethics) expectations and practices. Scientists are consistently tasked with communicating their findings to the public, and public interest in specific topics can increase or decrease through time. Projects that spark public interest tend to be more highly rewarded than projects that are important, but less eye-catching. At an institutional level, for example, we can begin to question how scientific achievements are rewarded and which kinds of approaches and outputs garner institutional support and prestige. The three factors discussed here are summarized in the table below.

|Factor  | RRI | Research Integrity |
| -------- | -------- | -------- |
| Who is (most) impacted by ethical dilemas?     | Broader society    | The research community     |
| Who is interacting?     |Researchers working with the public or study participants     | Researchers working with other researchers    |
| What shapes research?    | Public expectations and perceptions    | Institutional policy and culture    |

### The CARE Principles 
The CARE principles for Indigenous Data Governance recognize that current movements towards FAIR and Open research fail to fully engage with the needs, rights, and interests of Indigenous communities. While the FAIR principles encourage a more generous and open scientific environment, they do not take into account power differentials and historic contexts/ trajectories. Overall, the CARE principles address the complex of social, political, and economic relationships that have existed between Indigenous Peoples, researchers, and the broader world. The four CARE principles are:

* **Collective Benefit:** Data ecosystems should be developed in a way that ensures Indigenous Peoples derive benefit from the data. 
* **Authority to Control:** Indigenous’ people’s rights and interests in Indigenous data should be recognized and they should be empowered to control how data is used. Indigenous Peoples should be able to establish how Indigenous lands, territories, resources, knowledge, geographical indicators, cultures, and bodies are represented and identified within data. 
* **Responsibility:** Researchers working with Indigenous data have a responsibility to understand and communicate how their work is used to support the self-determination and collective benefit of Indigenous communities. 
* **Ethics:** The rights and wellbeing of Indigenous Peoples should be at the forefront of all research practice. 

![GIDA Indigenous Peoples' Rights in Data](https://figshare.com/ndownloader/files/39449659/preview/39449659/preview.jpg "[GIDA Indigenous Peoples' Rights in Data](https://figshare.com/ndownloader/files/39449659/preview/39449659/preview.jpg), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)")

### General Data Protection Regulation (GDPR)
If your research project involves the processing of data concerning living people, it may be subject to the General Data Protection and Regulation (GDPR). The GDPR is the strongest privacy and security law in the world and has been applied since May of 2018. The GDPR defines the rights of individuals whose data may be stores, the obligations of those processing personal data, methods for ensuring compliance, and sanctions for those who breach the rules. These penalties can be severe and GDPR regulations should be taken very seriously.

Personal data relating to an identifiable person falls under the GDPR. This includes information about research participants, but also the project team members too. There are also special categories of data that are considered sensitive which include race, ethnic origin, political involvement or opinions, religion, trade union memberships, genetics, biometrics, health indicators, and sexual orientation and behaviors. Information derived from a person’s physical and mental health data is also protected. If you would like to work with any of these kinds of data, talk with your supervisor early during the planning phase of your project. Additionally, it may also be advisable or necessary to consult with the [UNIVIE Ethics Committee](https://www.qs.univie.ac.at/en/services/ethics-committee/) or the [Data Protection Officer (DPO)](https://dsba.univie.ac.at/). If you would like help contacting them, you can consult with your data steward or contact the UNIVIE RDM team (rdm@univie.ac.at). 

### Working with Animals 
If your research project involves living animals, you may need special approval to begin your work. This is especially true if you plan to work with vertebrates or cephalopods. Different levels of permission are required for different types of projects. If your project is considered physically invasive, or causes significant psychological stress, your approval process will probably be more complex. If you are part of the Faculty of Life Sciences and are considering working with animals as part of your research project, you should contact **Herbert Gasser** (herbert.gasser@univie.ac.at) in the Dean’s Office. He can help you determine what permissions you will need and can give advice on how to proceed. Ethics aside, keep in mind that many journals will ask to see a record of your permits or ethics board approvals before they will agree to publish you research, so be sure to ask questions early and to save important documentation. 

![Raptor Fences by XKCD](https://imgs.xkcd.com/comics/raptor_fences.png "[Raptor Fences by XKCD](https://xkcd.com/758), [CC BY-NC 2.5](https://creativecommons.org/licenses/by-nc/2.5/)")

### The Nagoya Protocol
The “Nagoya Protocol on Access to Genetic Resources and the Fair and Equitable Sharing of Benefits Arising from their Utilization” (NP) is an international treaty that came into force on October 12th 2014. It aims to ensure that any access to genetic resources and its derivatives (e.g. metabolites, lipids, enzymes) is done under fair conditions and any benefits (e.g. commercialization, but also more general any type of knowledge gain) that stem from the utilization of genetic resources is shared equitably with the provider country. The NP **applies to all research and utilization of genetic resources, both for commercial and non-commercial purpose**, and includes applied and basic research. To comply with the NP, researchers must obtain permits for their planned research from the provider country and submit due diligance declarations in the user country.
For legal support with NP you can contact Sofiia Myklush (sofiia.myklush@univie.ac.at) at UNIVIE [Technologytransfer](https://transfer.univie.ac.at/en/team-and-contact/).
In addition, Kathi Kitzinger (katharina.kitzinger@univie.ac.at) is organizing an informal Nagoya Protocol “Stammtisch” (regulars’ table) at CMESS where everyone can exchange experiences with the NP.

### International Transport of Samples
Another important legal or ethical aspect you should consider is the collection and/or transport of international samples. You may need to secure special permits or allow certain inspections to take place before samples are allowed to leave their country of origin or enter Austria. You may also need permits to collect the samples too. Legal guidelines vary significantly by country, even if the countries are close to one another geographically or culturally. Investigate these requirements during the planning phase of your project so you can avoid surprises later. In some regions, permitting can be a challenging and time-consuming process, so it is advisable to start early and talk with other researchers who have worked with similar materials from the same countries. Much like permitting for working with animals, many journals ask to see import and/or export permits for samples, so make sure you save important documentation and abide by any laws. 

### Research using Private Funds 
We have one final legal tip before you move onto the section quiz. If your research is supported by private funds (for example, from a company), make sure you carefully read any legal documentation you are given at the start of your project. It is also a good idea to have a conversation with your advisor about any private funds you receive or funds they have received that fund your project. Make sure you understand who retains legal ownership of the data you create and if there are any other restrictions that might be placed on the data and its publication.
At UNIVIE you could contact the [Research Services](https://forschungsservice.univie.ac.at/en/) for legal advice and support with your private funds and your rights regarding the the research output.

### Quiz
Last quiz! We promise. Each question has at least one correct answer, but there can also be multiple correct answers. 

Sample collection and export processes are the same in most countries. 

      [[ ]] True
      [[X]] False
    
What are some examples of sensitive data under the GDPR? 

    [[ ]] A laboratory mouse model's genetic data
    [[X]] Personal data that can be linked to a living person
    [[ ]] Information about racial identity or ethnic background
    [[X]] Data about political beliefs or affiliations
    [[ ]] Biometric information from a Roman soldier    

I am a scientist, therefore I need not concern myself with the legal documents sent to me by my funders.

    [[ ]] True
    [[X]] False
    
The CARE principles are designed to take into account the complex social, political, and economic relationships that exist between Indigenous Peoples, researchers, and the broader world.

    [[X]] True
    [[ ]] False

## RDM Help at the University of Vienna
**Remember the University of Vienna has a whole Research Data Management Team available to help you with your research!**

**To find help, you can send an email to rdm@univie.ac.at or go to the totally awesome UNIVIE Research Data Management Homepage at rdm.univie.ac.at!**

![RDM Homepage at UNIVIE](https://raw.githubusercontent.com/feichtingerm/rdmlifesciunivie/main/images/RDMWebpage.PNG)

**If you are part of the Faculty of Life Sciences or the Center for Microbiology and Environmental Systems Science you can also contact your data steward directly.**


For the Faculty of Life Sciences, contact Emily J. Kate at emily.jean.kate@univie.ac.at. 

For the Center for Microbiology and Environmental Systems Science, contact Michael Feichtinger at michael.feichtinger@univie.ac.at. 

![The Upturned Microscope Dropping the Base](https://upmic.files.wordpress.com/2016/06/dropping-the-base.png " [Dropping the Base by Upturned Microscope](https://upmic.files.wordpress.com/2016/06/dropping-the-base.png), [CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/)")


Sources 
======================

Quotations
--------------------
**To make this course, we used resurces and text from a diversity of sources. If we quoted text directly from a source or we only lightly edited the text, that quotation is indicated by a superscript number. A list of those sources can be found here.**

^1^ ELIXIR. Research Data Management Kit. A deliverable from the EU-funded ELIXIR-CONVERGE project (grant agreement 871075). 2021. URL: https://rdmkit.elixir-europe.org/.

^2^ GO FAIR. Fair Principles. Accessed 2023. URL: https://www.go-fair.org/fair-principles/.

^3^ The Turing Way Community, Becky Arnold, Louise Bowler, Sarah Gibson, Patricia Herterich, Rosie Higman, Anna Krystalli, Alexander Morley, Martin O'Reilly, & Kirstie Whitaker. The Turing Way: A Handbook for Reproducible Data Science (v0.0.4). (2019) DOI: https://doi.org/10.5281/zenodo.3233986

^4^  Jeanne Wilbrandt: Research Data Management Intro Series: Coffee Lectures & Espresso Shots. (2023) DOI: https://doi.org/10.5281/zenodo.7573695

^5^ EDINA and Data Library, University of Edinburgh: Research Data MANTRA (online training units & data handling tutorials). (2017) DOI: https://doi.org/10.5281/zenodo.1035218


In-Text Citations
---------------------------
**If we included an in-text citation that refers to an outside study or resource, you can find the full reference here.**

Centers for Disease Control and Prevention (CDC). The u.s. public health service syphilis study at tuskegee timeline. 2021. URL: https://www.cdc.gov/tuskegee/timeline.htm.

Korenman, Stanley G. Teaching the responsible conduct of research in humans (RCRH), chapter 1. Los Angeles: University of California, 2006. URL: https://ori.hhs.gov/education/products/ucla/default.htm.

Videos and Images
---------------------------
**A link to the source material for the course's images and videos can be found under each item.**
