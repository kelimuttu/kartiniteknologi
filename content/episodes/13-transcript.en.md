+++
date = "2020-04-05"
description = "Transcript for Episode 13 of Kartini Teknologi with Adzkia Salima"
linktitle = ""
title = "Transcript - Episode 13 - Adzkia Salima"
slug = "13/transcript"
type = "transcript"
+++

**Kiki (K):** Hi everyone! In the midst of the corona outbreak, hopefully all is well. Anyway, we're back again with Kiki and Galuh here. And as usual we will be chatting with one guest, this time the topic is interesting because we have never discussed it and it seems like a fairly new topic in Indonesia. It's about bioinformatics. And with us now we have Adzkia Salima, she is a software engineer at Genetwister Technologies, right? Hello Adzkia, how are you?

**Adzkia (A):** Hi, I'm good.

**K:** How are things going amidst the corona outbreak? Is your family well?

**A:** We're good alhamdulillah.

**K:** Anyway, let's start from the usual, we usually start from the background. You used to study at S1 in IPB, then later in the Netherlands. In IPB you already majored in IT right?

**A:** Yes.

**K:** Can you tell us about how you first got interested in IT?

**A:** So actually I have a lot of interests, right? So I wanted to be a doctor, but I don't like the hospital environment, because I used to be hospitalized in the past too and I just don't really like it.

**K:** But not afraid of blood right?

**A:** No, but like I don't like the atmosphere of the hospital and it's scary, cold.... And also the commitment is high, so if for example you want to continue your study in doctor, you have to be a doctor. If not, it's a waste of money. Then when I was in high school, I looked at IT and there was like a lot of hype. That's when we had the Facebook boom, then Bill Gates, Mark Zuckerberg, isn't that right? It's possible that we are of different age, yes. But at the time I was like that. So it was like, so cool. And also my upperclassmen who were smart also ended up majoring in computer science, so I was interested so, and it seems like there are a lot of problems that can be solved by technology. It's also flexible, right.

**K:** So you initially wanted to be a doctor, then finally took IT. Anyway, talking about college, you went to IPB. Then... for your master's degree you took bioinformatics, right, why is that? Is there a story behind it?

**A:** I was interested in bioinformatics because I had read the Minister of Health's book at the time, her name was Siti Fadilah Supari. The title of the book is Saatnya Dunia Berubah (It's Time for the World to Change), it was when there was an epidemic like what we have now, but it seems we didn't talk as much about it then... it was the Bird Flu. It tells how all the genomic data is concentrated in the US. So in Indonesia, we all need to give the samples to WHO, then after that, they're the ones with the data, and they can't ... they're not open. Ms. Siti Fadilah Supari said that we are actually able to process the biological data. The problem is that the data is very important for making vaccines, and vaccines are truly a profitable business if you can make them. So, I was inspired by it, oh bioinformatics seems cool, processing biological data. From there I became interested in bioinformatics. But because there is no bioinformatics in Indonesia yet... well there is but mostly in private universities. But in the past there were no bioinformatics, so I was like, okay, I'd major in computer science first. Actually computer science had a lot of fun courses as well. It provides a really good foundation for the informatics. I was interested in subjects like algorithm analysis, so how do I make the algorithm efficient by applying the types of algorithms, data structures like that. And that seems to be the most beneficial when applied in bioinformatics, especially if there is another outbreak like this. At that time I thought about it like that.

**Galuh (G):** I'm really curious, if for example people with bachelor's degree in computer science, want to pursue graduate study in bioinformatics, what courses are the most relevant or the most relevant for master's degree in bioinformatics or for focusing on bioinformatics?

**A:** In my opinion, it's related to algorithm and development, like data structure, algorithm analysis ... maybe the name is different ... but back then that's the name  I think.

**G:** In my university it's called Design and Analysis of the Algorithm.

**A:** There's a MIT course too called Introduction to Algorithms. In MIT's open course. It's very useful.

**G:**  Which data structures or algorithms are most often discussed when discussing bioinformatics?

**A:** For me, it's usually parallel programming, dynamic programming ... search algorithm, with big data, how can we process it quickly.

**G:** Because the data that is usually processed is really big, isn't that?

**A:** Yes, very big. The problem with big data is that there is useful and useless data, so we must also be observant.

**G:** Hmm, interesting. What does useful data look like and how to differentiate what kind of data is useful and what data is not useful?

**A:** So in the structure of our DNA, in bioinformatics we usually look for a single nucleotide polymorphism, so nucleotide... nucleotides are A, T, G, C and so, so DNA consists of nucleotides. So if the nucleotide is different, that's what we are looking for, which is different from other species. Because per mutation can be useful to show a trait in the organism. So, to determine whether it is useful or not, we must know the annotation, so look again, for example, what genes are there, what protein it will be, stuff like that. We must know the biology and to know that we must combine the data from one genome with other data.

**G:** So what kind of data is usually stored? I only know csv, that's it.

**A:** For genomes, there are a lot of biological data. As for the gene data... DNA and RNA like that are stored in a file format like FASTA, so it's already in plain text. Then .. the information, information about the function of the single nucleotide polymorphism usually uses ontology or RDF. RDF is like a document where one entity describes another entity.

**K:** That is the entry if the data about DNA must be sensitive, right? Where did you get the data from?

**A:** In my company, from a company that is [inaudible]. But not really, not too sensitive, so there are also many on the Internet that are open source. So there is a lot of, genome data that is already there. Like [GenBank] (https://www.ncbi.nlm.nih.gov/genbank/), [National Center for Biotechnology Information (NCBI)] (https://www.ncbi.nlm.nih.gov/).

**K:** Does it mean that the data is not tied to a particular identity?

**A:** Yes, if the data is about humans then it's sensitive. But not if it's plant data. But there are also sensitive plant data, for example if it's the result of a company's research, then it's not allowed. But a lot of data is also open source.

**K:** In Bioinformatics, there must be a lot of biology. In addition to biology, what else did you study in postgraduate study?

**A:** Hmm ... so there is about computer science, about biology too. So we also continue to be taught computer lessons, algorithms in bioinformatics, machine learning, advanced statistics ...

**K:** How much is the portion between IT and biology?

**A:** For me because I already had my degree in computer science, so I took a lot of biology. Meanwhile, for people whose undergraduate degree is in biology, they take a lot of computer science courses.

**K:** I see. Let's talk about your last job. So actually we know Adzkia from Twitter. Then on your profile you wrote that you work at a company which is like Tinder for plants. What do you mean by that?

**A:** Yes, so the original name isn't actually Tinder for plants, but CROPaware. So it's a software to save and browse genetic data from a plant. Because a lot of people asked, I was a bit confused about explaining how it worked, so I just said it was like Tinder for plants. Tinder is like a dating app, so we're looking for a suitable partner for us. In CROPaware too, plant breeders can get the genetic information needed to breed their plants. So it's like plant match-making.

**K:** Then what are the results, after the plants are matched? A breed that is more superior, or ...?

**A:** So the research questions can vary. For example, I want a new breed that is able to withstand disease, a breed with a better color, then... it can also taste sweeter, at that time there were tomatoes like that.

**K:** I see. Does this include making the process of making GMOs or not?

**A:** It can be used for GMOs, but for GMOs  wemust modify the DNA directly outside. But if it's mating it's not GMO.

**K:** Ooh, I see. So you can say that this is more natural.

**A:** Yes, it's more natural.

**K:** Okay. Then who uses this services usually?

**A:** Food and agriculture companies.

**K:** So like they came to you with their own problems, for example, "I want my tomatoes to be sweeter", like that?

**A:** Yes.

**K:** Wow, so cool. In Indonesia itself are there companies like this, or are you not really aware about it in Indonesia?

**A:** There is no commercial company like this.

**G:** If I want to make my tomatoes more fresh, without the help of software, what do people usually do? I'm totally unfamiliar, so without the software, what is the process and how long does it take?

**A:** That is usually a by chance, so all the plants will continue to be mated, it will take a lot of experiments until we find a good one.

**G:** Trial-and-error, right?

**A:** Yes. So it might take years. If we use software, we know, oh this has this gene, others have this gene. And between genes there is an antidote to one another, so although both are superior seeds it doesn't mean that the breed can be superior too, it's not certain. So if you use software it can be faster.

**G:** It's similar to using Tinder, maybe looking for a match is faster with Tinder.

**K:** In the traditional process, we have experiment ourselves. If using technology, does it mean that only from the DNA, the result would definitely be suitable without us having to test again? Is it certain that the breed will be a better one? Or must it be tested too or we can find out from the results of the analysis?

**A:** Still need to be tested too, because it's impossible to be correct 100% so there must be something we don't know that is contained within the organism. So still have to be tested. But it's clear that if we use technology, it can be faster.

**K:** I see. And if for example in your own office, is there another team who does the testing?

**A:** No, so we usually write a report and we give it to the agrifood company. But for us, we usually use in silico validation, so it's validation but based on statistical and mathematical calculations.

**K:** Means the task of proving it is in the hands of the client, isn't it?

**A:** Yes.

**K:** What's your role in your team?

**A:** I work on the CROPaware web application, working on the parallel computing and distributed systems parts of it.

**K:** What is the tech stack you use usually?

**A:** The language is mainly Java, we use Spring Boot. Python for combining our application tools, and also for parallel programming, we use Scala. Database, we use Cassandra, MySQL, RDF. For web development, we use Git, Jenkins, Docker because we also have microservices.

**K:** Wow, there are a lot of tech stacks too. How many people are there in your team?

**A:** There are 6.

**K:** There are 6 people and that's the whole development team?

**A:** The whole software development team.

**K:** Oh wow.

**A:** So like everyone does everything, but each of us has a specific interest. So we are given responsibility there.

**K:** Okay, wow. And what about you?

**A:** Distributed system. There is also someone focusing on frontend, so they worked on the frontend. But sometimes even if there is a bug I can just work on it.

**K:** But how do you like it so far, do you regret taking IT or you feel like ... this is the right spot for me?

**A:** No regrets at all, even though we don't work in the field, in my opinion it's fun even though say that I don't work in IT.

**K:** Yes. IT is a field that intersects with many things, right? So we already talked about the technology. How about the business model itself, can we discuss it or not?

**A:** Yes. Maybe before we talk about Genetwister I want to explain first the big picture. So the Netherlands is the second largest exporter in the world after the US, even though the Netherlands is very small. What makes them more advanced than other countries is that they are serious about implementing their technology. Well, even one agrifood company can have more than 5 outsourcing biotechnology companies, to research the plants they have. Well, here Genetwister is one of these biotechnology companies. So Genetwister has 5 shareholders, agrifood companies in the Netherlands and throughout the world. So they are like the research and development department of these companies. So it's a small part of the companies.

**K:** Which means you can say that the company is the research department of the other companies?

**A:** Yes.

**K:** We talked about the Netherlands being the second largest exporter after the US. We know that they have a small land, how do they do it to ... like to make it happen like that even though they only have a small land?

**A:** They have a small land, the weather is really bad, the wind is really big, but maybe because of that they turn the brain around so how can they meet their needs. But from there they become very advanced. They have a lot of greenhouses. We usually do farming in the fields, but they do farming in their lab. So they produce a lot ofproducts, there is no crop failure... I've read in the tulip museum in Amsterdam, their motto is "God created the world, and the Dutch created the Netherlands". So the Netherlands is manufactured, and everything is planned.

**G:** In Indonesia, what do you think about our progress is related to bioinformatics or tech agriculture?

**A:** In my opinion, in Indonesia for agriculture technology, it's not there yet. There are companies that use the same technology as in the Netherlands to process biological data, like research at LIPI, Eijkman, it already exists. But it is more for the medical, for humans. So for agriculture, it's not there yet.

**G:** But actually if we start to use agriculture tech, is it possible or it's fine the way it is right now, like we don't need to use tech? Or do you think it actually can provide a really huge value and we just haven't caught up to it yet?

**A:** I think it will be very beneficial for agriculture in Indonesia. We really have a lot of harvest failures, like that. Many have illnesses, and also our seeds are still dependent on foreign companies. They can do whatever they want to control the price of seeds. So I think it's really important that we can be independent too.

**G:** If we want to implement agriculture tech, who should actually change or take action? Let's say whether it's government by opening data or something or maybe we need more software engineers to work on this field or what?

**A:** In my opinion, from all stakeholders in the community, starting from... there must be something that kics it off. For example the government, they must encourage companies, give relief to support companies, startups in agriculture. Then the computer science graduates also have to start looking in that direction too, because if we don't, who will?

**G:** I see, it's interesting, because honestly as a person who graduated from computer science and I don't know much about bioinformatics and its applications. I also just learned from talking to Adzkia that there are a lot of potential in Indonesia, and if there are many software engineers or tech people who work in this field, surely this field will advance. We are also an agriculture country at the first place.

**A:** I'm always like, I don't understand, we are an agriculture country, but we still import rice, we still import everything ... we can import things that we can do by ourselves, import corn, import beans. Why is it so.

**K:** According to you, why in Indonesia we haven't adopted many agricultural technologies yet?

**A:** We haven't really done things to combine computer science with biology. We have started but maybe the awareness is not there yet. When it comes to agriculture we usually hear things like, "ah, what the heck is agriculture".

**K:** In fact, I think agriculture is actually something that will last, everyone will need to eat and everything. Looks like it's one area that won't expire with time.

**A:** Yes. Also, government policy will help a lot.

**K:** What kind of policy?

**A:** For example the government must set that, okay, we must be self-sufficient when it comes to food. Then universities should make majors or curriculums where students learn about agriculture. For example computer science students also have  to study agriculture or something like that, or biology, bioinformatics. We also need a push from the government. We are too comfortable in Indonesia.

**K:** In terms of agriculture, in your opinion actually if ... if we look at agriculture now, is bioinformatics applicable? I think it would be really difficult, because people would be [inaudible] using the traditional method, right?

**A:** We can introduce bioinformatics into agriculture, it can be done because the farmers themselves have something called Farmer Groups, so all the new technologies given to farmers will be through Farmer Groups where they have this workshop. So you can use farmer groups like that.

**K:** So it's like leveraging a group that already exists to introduce this technology.

**A:** Yes.

**K:** Hopefully Indonesia will catch up. Let's discuss about psychology.

**A:** Yes, I really like talking about this.

**K:** I'm also the type of person who likes MBTI, like that, psychology stereotypes. Then, I saw you [tweeting about MBTI as a programming language](https://twitter.com/perrenellle/status/1229886610352852995/photo/1), right? I was curious about how you could produce such an analysis.

**A:** That's because I often watch memes like, MBTI as country, MBTI as celebrity, then I keep guessing and I think I'm good at typing people. Then when coding for example, when  using functional programming, I think that's really INTP, it's complicated. Then for example if you use Java. My manager... I like typing, right, and he looks like an ISTJ. Then he said, "Anyway, whatever happens we have use Java. Because Java works for everything."

**K:** Rigid.

**A:** Yes, the person is rigid. Meanwhile INFJ, it's JavaScript, it's abstract but they are all about the community, they are very concerned about the community, so oh that's really JavaScript.

**G:**  What about your type?

**A:** I'm INTP. I like Scala. But functional programming in my opinion is very interesting. But I haven't learned Haskell yet, quantum computing... those are things I find interesting but I don't have time yet.

**K:** What about you?

**G:** I usually get INTJ

**A:** Oh Java 8.

**G:** I don't know the difference between Java 8 and Java.

**A:** Java 8 is more about functional programming, that's it. So they use lambda. Usually we use for loop, if Java 8 it's also mostly streaming.

**G:** I have never explored Java again, if it's the usual Java, it's Java, right? Kiki what about you?

**K:** I'm INFJ.

**G:** JavaScript.

**A:** Do you like JavaScript or not?

**K:** I have no idea since it's been years since I actually code, but I actually do use JavaScript before ... yeah, and so far so good, I just like it, but not like ... I like JavaScript the most so.

**A:** Anyway, according to me, NF people are advocates, influencers are like that. Anyway, programming languages ​​that concern the community.

**K:** The community is strong, right? 

**A:** Then the Explorer, I have never seen an SFP people, like party animals, I have never seen an SFP person coding, so in my opinion... GUI game for learning programming.

**G:** I think I have an ESFP friend, but mostly they are designers or UI UX.

**A:** But they don't code right?

**G:** On the job or not, they coded in college too, but now they're designers. But why Bash is ESTJ?

**A:** Bash? It is like ISTJ, it is strict but because it is an extrovert, it likes to order things.

**G:** For SQL, why ESFJ?

**A:** ESFJ is like a loving person, and ESFJ is like a typical housewife to take care of the database. SQL is very housewife I think.

**K:** This is so exciting when I read it too. So if you're confused about what programming language to learn, maybe search for one that matches your MBTI personality. Any plans for the future or other activities that can be shared?

**A:** I want to deal with or learn more about neuroscience or molecular psychology. So combining psychology but underlying biological [inaudible] why, also sharing my writings.

**K:** Ooh. Do you write as well?

**A:** I write on my blog.

**K:** Please share your blog later ya. Okay, that's our conversation with Adzkia, it's really exciting to talk about a topic that we rarely discuss, because in Indonesia itself it seems like it's still not common, not many people know about this technology. So thank you very much Adzkia for coming and sharing with us. Thank you!