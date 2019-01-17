<style>
    ul{list-style-type:upper-roman;}
    #split_mobile{
        display: flex;
        flex-direction: row;
    }
    #mobile_screen{
        width: 46%;
        margin: auto;
        height: 60vh;
    }
    sup{
        color: red;
    }
    a{
        color: skyblue;
    }
    em{
        font-weight: bolder;
        color: #ff6363;
    }
    @media only screen and (max-width: 825px){
        img{
            width: 250px;
            margin: auto;
            text-align: center;
        }
    }
</style>

# An Introduction to ml.sftwrs

## Table of Contents

- [The ml.sftwrs Initiative](#i.-the-ml.sftwrs-initiative)
- [History](#ii.-ml.sftwrss)
- [Philosophy](#iii.-philosophy)
- [Navigation(mlsftwrs.ml)](#iv.-navigation)
- [Objective & Plans](#v.-objective-and-plans)
- [Fields of Interest](#vi.-field-of-interest)
- [Who is ml.sftwrs for](#vii.-who-is-ml.sftwrs-for)
- [Publications](#viii.-publications)
- [Version2.0 & Future](#ix.-versioning-&-future)
- [Copyright & License](#x.-copyright-&-license)
- [Conclusion](#xi.-conclusion)
- [sources](#sources)

## I. The ml.sftwrs Initiative

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ml.sftwrs is defined as  ml(Mali) – sftwr(software) – s(sets), and pronounced as M-L Softwares, or Mali Softwares. It is an initiative set in motion with a simple but strong objective: solve problems using computational science in Mali.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Over the last half a century there has been an explosion in the field of Computer Science in general, from the design of the Unix operating system(OS), high level languages, and compilers at Bell Labs, to the GNU operating system project, to the world wide web, all the way to the works presently being done by the many software companies such as Microsoft, Google, Amazon and on.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nothing really has impacted our day to day life in mass numbers like this prior to the introduction of computer systems to my recollection. The introduction of software has proven fruitful in our lives. Note that I will emphasize on software here, hardware essentially is a medium in which software is presented, and delivered – although it is an extremely important part of a computer system. I like to think that the most valuable part is software, I am sure a hardware engineer would disagree. This is a philosophical discussion I will have to get into in a later post. For now, let us just assume that software is the most valuable part.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With that assumption, software’s power in general has been fairly impactful in the developed world, everything has been computerized — well almost everything. Automation has taken over all industries in some form or shape. Manufacturing, the financial market, military, transportation all of these use computational models to perform as they do these days. This widespread in technology, although in some length has reached the non-developed countries, it has not been as rewarding as it has in the developed world.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A country like Mali is missing out on all of the advantages that comes with computerization. A prime example of this is the health care system, food production, financial market, educational system. All in all the entire nation's tech infrastructure is underdeveloped, or completely undigitized. There is no denial that platforms, like Facebook, and Google has reach a number of people. A 2018 report<sup>1</sup> from the International Telecommunication Union(ITU) reported that 12.7% of the nation are internet users, with a 3.2% households that own a computer. These figures are for a country with a growing population of 18.54 million as yielded by a Google Search. These are some very depressing numbers and not to mention that vast number of those internet users are social media users(not in the occasional use sense), these are the typical users who only go online for the mere use of a social media platform. I do not have an exact figure on Facebook users, but based on personal experience the platform has a really strong user base. Which I must point out is totally fine.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The main problem is that productivity is then disregarded. Similarly out of those computer users many of them also only see their computers as media streaming, typing, internet browsing, and gaming devices – which they are of course, but they are also more than that. And this is no fault of the users/owners as they are really not given anything other than the standard for-profit bundle of software packages now being called OS. I am referring to OS X, and Windows of course – these OSs come packed with hidden costs. Costs that are affordable for a typical user in a more developed area of the world, but is fairly luxurious for some one in a third world country. For example, the new macOS Mojave is 6.1GB as listed on Apple’s website. It would be really time consuming for an Apple mac computer owner in Mali to upgrade to this version as the typical users did not have access to a broadband internet connection last I checked. Another major downside of owning these devices is that productivity applications are monetized. All of these make these platforms not really suitable for people without proper internet connectivity, or financial stability as you would find in a more developed world area of the world.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ml.sftwrs is here to challenge these situations. Not just internet connectivity problems, but ml.sftwrs pledges to simplify life for the every day folks, make operational processes much simpler for businesses, optimize government’s work through computational science. At this point I should point out that ml.sftwrs is computational model focused rather than product oriented, it attempts to standardize anything that is believe to contribute to the development of the nation, in a research and development approach(R&D). In using abilitiees in computational science, intelligent systems, automation, and computer networking ml.sftwrs works on advocating the implementation of computer systems in Malian life in a productive, and empowering manner.

## II. ml.sftwrs

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ml.sftwrs idea first came to life after noticing that there is a lack of order in any of the areas that you really look into in the Malian government, especially after the sets of events<sup>2</sup> that occurred in 2012. Reading any publication relating to Mali was not only depressing, but majority of the issues expressed sounded fairly solvable using basic intuition, and or taking an analytical approach. Ultimately in the fall of 2015, I approached an actual government agency in an attempt to closely observe how they operate. This really opened my eyes as I found out that in 2015 a government agency did not have any IT infrastructure set in place. This included lack of internet connectivity, proper tools for the task required, or even an updated Windows Office(main program being used by the office), a secretary apparently had a windows 7 32-bit workstation, but she appeared to have no general systems knowledge, and only could fill out a Word form(important part of the agency’s work). To make matter’s even worse, I decided to design a windows based interface that had a much cleaner form, and setup two separate backup systems as the information being recorded was fairly sensitive, most importantly automate majority of the tasks required from saving to reporting in – to my surprise the office expressed that they prefer using the older method(Guaranteed that the platform was a bit buggy, still surprised nonetheless). As a result of this I really had to think of way to change this way of life. It is that brainstorming that led to the idea of ml.sftwrs.

### ml.sftwrs1.0

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There has been an initial implementation of ml.sftwrs. Due to the fact that I lack an indepth experience in some of the fields of interest, and the amount of workload required to accomplish this objective, I decided to work with a few other individuals – the premise of this initial version was to fund ml.sftwrs by doing contract work for established third-party companies, and compete in kaggle competitions. This funding was intended to get a team to work on the vast numbers of projects. In retrospect this entire version was not how I had imagined ml.sftwrs to work. This was the fruit of the accumulation of personal problems I was dealing with and listening to individuals who and I had imagined this entire initiative differently. Ultimately, a decision was made to halt this version, as everything was going south.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Rather than completely give up on the project, I have decided to revamp that version, and reform ml.sftwrs to how I had originally imagined it. A new version, ml.sftwrs2.0 with a different philosophy(discussed next) and completely independent.

## III. Philosophy

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ml.sftwrs follows the same model as most open-source projects, except that I have decided not to label it an open-source, or free software movement. ml.sftwrs aims to take a R&D approach in its works. Any of the projects published under the cover of ml.sftwrs will not be for-profit. All of the projects are concentrated on a single geographical area and that is Mali. The initiative aims to build models that will focus on a specific problem in Mali, and one problem at a time. Although I occasionally think of it as an open-research, the reality is that it is an individual research, self-funded, and worked on in my own time. This initiative has come to life as a passion project – hence it ought to only be worked on with that mindset. A passionate individual looking to make an actual change with their skillset.

## IV. Navigation

*A chrome browser is highly recommended.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Lets now go over the mlsftwrs web app. This is a single page web app that serve as the entrypoint to the world of ml.sftwrs. This app was designed to accomplish three primary tasks: source code repositories, publications/notifications, and authentication. The present version is partitioned into multiple functionalities each accomplishing a specific task. Here is a brief overview of the ml.sftwrs web app.

Once you type “mlsftwrs.ml” you should be presented with the following screens: fig.1.1, fig.1.2 computer and mobile respectively.

![fig1.1][comp]

fig1.1
<div id="split_mobile">
<img alt="fig1.2" id="mobile_screen" src="https://tinyurl.com/y7u6f7yv"/>
<img alt="fig1.2" id="mobile_screen" src="https://tinyurl.com/y8awccmy"/>
</div>
fig1.2(second image is the menu view)

>
*Note that older browsers are not supported. Internet Explorer is also not supported.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mobile users ought to install the web app for the best experience, this is done by clicking on the install app button shown in fig1.3 or open the web app in a chrome browser then add to homescreen from the browser's settings menu. The landing page or by taping on the menu icon in mobile, presents you with all the different options available within the web app -- they are the followings:

### Authentication(ml.sftwrs auth)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Authentication is conducted by the ml.sftwrs authentication system, instead of a third-party system, or implementing an authentication system for each of the project, it is attempt at user focused cluster. Authentication is presently not required for the web app itself.

### ml.finance

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ml.finance in itself is a ml.sftwrs project. The project rooted when I was learning about data-science, all of the resources I was using at the time were datasets from American, and European sources. As result of this I decided that I might as well use some datasets from Mali. The financial sector is the only sector where I was able to find a dataset big enough to do anything with it. As I was playing around with all of this data, I realized that there is so much that can be done with it. At the time, I was using a client – server model to do basic fetching for own projects, which resulted in the writting of a small API. Later I asked my self these questions: How useful is this dataset? What are other countries doing with similar datasets? Can I do anything useful with this dataset? These questions led to the development of the ml.finance platform. Briefly, ml.finance is an indexed database, API, that hold real-time information on companies in Mali, it is an attempt to centralize the entire financial sector while providing clear information on its relationship with other industries. ml.finance will be discussed further in the accompanying whitepaper once the platform is fully up and running.

<em>Patching things up, and reviewing for non-obvious bugs. A full test version is due to be deployed soon.</em>

### ml.plexus

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This is the original ml.sftwrs project. It is still currently under-development, but with the recent surge in blockchain technology, this idea is coming to life in a timely manner. The premise of the project is:  A p2p decentralized protocol based a set of clusters. Presently, visitors are presented with a form to access the ml.sftwrs portal upon taping the ml.plexus button, this is where the current source code, and the project design whitepaper draft is found. Only those given access keys will have access to this platform – as the portal is a personal home server, for security reasons.

<em>*</em>Note that ml.finance is expected to be one of the clusters of ml.plexus.

### ml.blog

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Perhaps this is where you are reading this post,  ml.blog serve as where the occasional publications are published relating to a platform being presently worked on, or an introduction to a platform, similar to this exact post.

### Regular Web Contents

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Faqs and About(Initiative in mobile) both do exactly as the name suggest. Frequently asked questions will be answered in Faqs. About will hold an overview of the initiative.

### Push notification

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As mentioned above mobile users should install the web app as the platform was designed with that mindset. The occasional notification, can easily be send to anyone who has the application installed. Due to the fact that it is not a native application, it will not be as resource consuming, and is also secure.

## V. Objective and Plans

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The intent is to have at least a documentation on all of the aforementioned projects, and those not mentioned yet, describing if they will work, or if they will not for the country - and if they do how to get it up and running as quickly as possible. All the projects are regarded as research projects, going through trial and error, hypotheses, and experiments. A quick solution is not expected. Because of the complexity of the subjects and the convergence of multiple fields projects are worked on in a subjective manner, there is no specific development timeline. And an individual working on fields that each of which take years to master, it should be clear that these projects will not be an overnight work. The primary plan however for the time being is to introduce the concept, and work on projects from my projects stack, and see how it goes from there.

## VI. Field of Interest

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ml.sftwrs fields of interest are the ones mentioned earlier. To reiterate they are the followings: Intelligent Systems, automation, and Computer Networks. These are the accumulation of the fields that I believe could make a major impact in the current Malian climate. Lets take look at each in an introductory manner.

### Intelligent Systems

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This is an accumulation of multiple fields in its self. It is a modernized version of machine intelligence, it adopts all the works done in past and complements that with the most recent discoveries in the field of artificial intelligence such as deep learning, amazing work in natural language, and speech recognition. Intelligent systems must be introduced in Malian industries. ml.sftwrs intend to use this field to accomplish the necessary modeling for the work being done by the many Malian industries.

### Automation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Automation and Intelligent Systems goes hand in hand. Automation provides an accuracy that is otherwise not found in a non-automated environment, and remove the redundancy that comes with some of the works being done in the nation. This field in conjunction with embedded systems have made impeccable change in the world. ml.sftwrs’ automation intend to center around Internet of Things – which is an accumulation of the fields of interest and embedded systems.

### Computer Networks

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Although Computer Networks generally implies TCP/IP. ml.sftwrs is taking a different approach into computer networking, in observing and studying the works that have been done in the fields of distributed systems, such as the roofnet project, and most importantly the blockchain technology. ml.sftwrs intend to reintroduce computer networks in their full capacity, not only decentralized(not politically), but also security oriented. I should mention that by computer network I am referring to the software side of things such as workplace infrastructure, communication. The concept of internet connectivity or internet speed are not a focal point, since it really would not do you any good to have a fiber and not have the right tools to use it with.

*Decentralization is discussed further in ml.plexus' whitepaper.

## VII. Who is ml.sftwrs for

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In a nutshell anyone interested – although an emphasis should be make on the fact that it is made by a Malian, for Malians. Also ml.sftwrs is directed toward information science officials, hobbyist, or scholars, all of the publications written, tools developed under ml.sftwrs will involve a level of technicality that only someone with a high level of technical awareness will have an understanding of the concepts. Case and point is the ml.finance project’s API, one has to understand how a HTTP request work, how the supported languages work presently(Python, C), and most importantly how web services work. It should be point out that there will be attempt to make the publications less technical; however due to a lack of authorial skills, nothing is guaranteed.

## VIII. Publications

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There are four major type of publications that will be published by ml.sftwrs. Blog posts, whitepapers, research papers, software documentation.

### Blog

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Blog posts as mentioned in ml.blog section are occasional publications for updates on projects.

### Whitepaper

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Serve as the full specifications for a project, this include hypothesis, modeling, and necessary information for the project. Except for the main web app, every projects will have an accompanying whitepaper.

### Research Paper

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A fully fledged research paper is published on every project as evidence, and for those interested in having an in-depth understand of the project.

<em>Note that at the moment I am in now way an expert scholar, I am a hobbyist working  on problems I believe I might be able to do something about.</em>

### Software Documentation

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It is impossible to have a successful open-source project without documentation, or any software project for that matter. All software related projects will have a full documentation for use, and contribution.

## IX. Versioning & Future

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;No one really knows what the future holds, all we can do is plan as precisely as we can. At the moment there is no intent to upgrade ml.sftwrs to any other version, since ml.sftwrs2.0 came to life as a result of a initial failed version, a new version would imply similar cause, and it would be best to hope that something like that never happens again. The only future plan of ml.sftwrs is to work on the projects as originally imagined without person life, and or political reasons interfering with it. It is after all independent of anything that can really hold it back.

## X. Copyright & License

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mlsftwrs will make attempt to avoid proprietary items for all of its projects. All the projects will try to build everything from scratch or otherwise use an open-source that has a flexible license. A major one of this is the GNU project. Any of the projects that I work on are not licensed I am more interested in implementing solutions than the credit/financial gain aspect of things. Due to my lack of knowledge in the licensing arena, all the projects will be hosted in a personal repository, and will be flagged with a ml.sftwrs copyright – this flag is present merely for accountability reasons, in case I may have violated someone else’s license or something along those line, I would want to be personally liable for that.

## XI. Conclusion

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We’ve reached the conclusion of this introductory post, briefly ml.sftwrs is an initiative set in motions as a passion project to solve the most ambitious problems in Mali. In using expertise in Intelligent Systems, Automation, and Computer Networks the initiative aims to challenge the currently under-developed Malian tech landscape. ml.sftwrs would like to introduce – the aforementioned fields in the day to day life of Malians. ml.sftwrs’ goal is grandiose but even achieving a fraction of this goal could lead to a domino effect that could to change an otherwise obscure future for a growing nation.

### Sources

[comp]: https://tinyurl.com/ya5dlort

<sup>1</sup>[https://www.itu.int/net4/itu-d/icteye/CountryProfileReport.aspx?countryID=150](https://www.itu.int/net4/itu-d/icteye/CountryProfileReport.aspx?countryID=150)

<sup>2</sup>[https://www.bbc.com/news/world-africa-13881978](https://www.bbc.com/news/world-africa-13881978)
