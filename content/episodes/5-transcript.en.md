+++
date = "2019-08-18"
description = "Transcript for Episode 5 of Kartini Teknologi with Vanya Valindria."
linktitle = ""
title = "Transcript - Episode 5 - Vanya Valindria"
slug = "5/transcript"
type = "transcript"
+++

**K (Kiki)**: Hi everyone, we're back at Kartini Teknologi with Kiki and Galuh here.

**G (Galuh)**: Hello.

**K:** This is our first time recording onsite, usually we record using video conference, but now we have a special guest and we happen to be able to do this recording together... so there are three of us here, and our guest is Vanya.

**V (Vanya):** Okay, I'm Vanya, and I currently work as a machine learning researcher as well as a research scientist. My background is actually machine learning, but my passion is more towards technology and music too.

**K:** I want to ask about your background. Where do you come from?

**V:** I'm from Jakarta.

**K:** Okay... so I'm also curious about your educational background, where did you go to college from your undergraduate until now?

**V:** I majored in electronics at ITB for my bachelor's degree, but the sub-major was in biomedical technology. For my master's, my major was computer vision and robotics. I did it in Europe under the Erasmus Mundus program. I did it in three countries: the UK, Spain, and France. I moved every semester, so I was also traveling and learning the European culture as well, because it's a program under the European Union.

**K:** So was the curriculum connected, from one university to another?

**V:** At the UK it was more about robotics, and in France it was more about computer vision, but the modules were indeed connected. For my PhD, I did it in London, in Imperial College London. It was about machine learning but for images.

**G:** It seems that you do have a lot of interests, from technology to music. What made you interested in technology specifically, for example when you were starting college, why did you decide to major in electronics and then computer vision for your masters?

**V:** I was interested in technology from when I was in junior high, high school... it's kinda cool, being able to create something. So I've liked technology from when I was in high school or junior high school. For music... I've always liked it from when I was a kid. For technology, it's more like because I like something new and I want to create something.

**G:** I see, because technology is like... you have all of these powers to create something new.

**K:** You have very specific expertise, in AI, in machine learning. And AI is one of the newer technologies, especially in Indonesia. It seems like there are not yet a lot of people who understand and work on AI. Based on your experience, how is the application of AI so far?

**V:** Actually I started learning AI when I was doing my PhD. During my undergraduate studies I fell in love with medical technology, like medical image analysis, how we can analyze medical images. But now... we use machine learning to analyze everything, so we're following the trend. But actually, AI is not new. Maybe it's becoming more prominent recently, especially computer vision since the computer vision challenges back in 2012. Maybe the reason why it's becoming more prominent is, first, we have big data—there are more data available now. Next, the computing resource, like GPUs, NVIDIA—they're becoming more advanced and are now able to process such a huge amount of data. For the tools, people can now use deep learning, neural networks. Back then when I was doing my undergraduate degrees, around 2006, I was using neural networks that only have one layer. Now it's becoming more advanced and the development is very rapid. In Indonesia... there are now many companies that use AI—computer vision, NLP, chatbots... for computer vision there are already a few e-commerce companies that are using it, they've done many researches in AI. And there are also many institutions that also do biomedical image analysis.

**K:** Institutions like hospitals?

**V:** Like universities... such as Binus. It's heading towards there, companies and institutions.

**K:** Yeah... I'm also curious, you said that you're a research scientist, and also a machine learning researcher.

**V:** Actually it's all research.

**K:** Okay, so what's the difference?

**V:** Actually both are the same, both are working on research... building methods that can improve the analysis. In machine learning, researches are developing very rapidly, so we are racing with the trends. We also keep improving the accuracy too.

**G:** What are the challenges in applying AI, especially in the medical field? What are the challenges that people are facing now?

**V:** Actually there are more challenges in the medical field, and not just in Indonesia. Be it in the UK, in the US... because for medical purposes, there are more procedures that we have to go through, like FDA approval. Here we probably need approval from Depkes (Indonesia's Ministry of Health), because this has something to do with people's health. One of the first challenges is usually the data—you need to have reasons from hospitals, ethical approval... and then for the ground truth, we need doctors or clinical person. To determine what's the diagnosis, what are the diseases, we need ground truth or the doctor's opinions which may be subjective. That's the challenge. For clinical needs in Indonesia... from the technical side, the computing resources, like the computer specifications... for medical images, the archives have to be properly stored. In radiology, there are systems like PACS and DICOM. And usually, the data is very large. For the approval system, sometimes the challenges are in the clinical people, like doctors or radiologists. Maybe it's not just here but also out there, maybe they feel something like... "why are you replacing me? You want to replace radiologists..." but the truth is, AI will not replace radiologists or doctors. AI will only assist to diagnose, to help, the diagnosis decision is still made by the doctor. This system will just help to make the process easier. For example, it can take a long time for radiologists to create ground truth, to mark the scans... AI can help with that. Back then perhaps the term computer-aided diagnosis was more well-known. Actually even from back then, the main purpose is just to help.

**K:** So it's more like complementary, not replacing the human resources.

**V:** In the UK there's a company called Babylon AI, it's also for healthcare... it's not chatbot, well kind of like chatbot but their AI can also help diagnose, they can use NLP as well. It's pretty big there.

**K:** So the platform is called Babylon?

**V:** Yes, it's called Babylon. They also work with doctors there, so of course they can't do it alone.

**K:** In college we have a class called image processing. What's the difference with biomedical image analysis?

**V:** It's actually the same, it's just the images are different. For image processing we're learning more about the techniques that we can use to process images, like regular images, photos. For medical image, it's just the images that are different, for example in medical images there are radiology scans, like MRI scans—magnetic resonance imaging— or ultrasound scans of fetuses, stomachs... or scans from CT scans, or surgery videos... like laparoscopy, it also counts as medical images. So we actually can do analysis from surgery videos. We can also do analysis using medical images such as of biopsy cells, we can analyze what's the type of this cancer cell. So in medical image analysis, the image that we are analyzing is specific to medical images. For the techniques though, we can use general computer vision techniques, but perhaps the processing methodology will be more specific to radiology or cell imaging.

**G:** If we want to do biomedical image analysis, what are the steps that we need to take?  Maybe from the data gathering process until the analysis is done, generally?

**V:** Usually we work with hospitals. So there are also experts from the clinical field, because the data is also the hospital's data. So first, the data. After we get the data, we ask the doctors what are their needs. So for the ground truths, they're the ones who determine if this image shows someone who is sick or not, is there any problem with this image or not. After we get the ground truths, then it's our turn to work—from the research or engineering side—to build a model, let's say a machine learning model trained on the ground truth data from the doctor. Then we validate, we test again with those data... if the accuracy is still low, we iterate the model again, we keep iterating until the doctors are satisfied, until it matches their criteria.

**G:** How long does it usually take for one project or analysis?

**V:** It depends on the project. Usually around four, five, well four to six months. But it depends.

**G:** For biomedical image analysis, what technology do you use, or what technology stack do you use, programming languages, or maybe softwares that you usually use?

**V:** Now everyone uses deep learning, so it's already end-to-end. What we use is standard deep learning library, like TensorFlow, Keras, Python-based... but back then when I was getting my bachelor's and master's degrees, I used MatLab, C++. Back then I still had to do feature extraction, detection, pre-processing... but now everything is already end-to-end using deep learning libraries.

**K:** How many images do you usually need to train a model using deep learning?

**V:** Ideally... well, usually, sometimes we ask them back—how many images do you need? For example, in radiology, we had 35 patients, and with 15 organs the results were quite good. We can automatically detect 15 organs from whole-body MRI scans of 35 patients. That's actually quite good. Of course, it would be better if we have more, but we have to make do with it if that's all we have... because making ground truths is exhausting for doctors, so we'll just use what we already have. We'll then adjust to it, although actually the more the better.

**K:** Aside of AI, what else have you worked on in the technology field?

**V:** When I was doing my undergraduate degree, I worked on biomedical image analysis, because my interest lies in health technologies. However I was more focused on the eyes, for example when someone has diabetic retinopathy, we can see from their fundus retina whether the person has diabetes or not. With computer-aided diagnosis—which is also image processing—we can detect where the retina leak happens, and from the fundus image we can see how severe is the diabetes. Our technology aids the diagnosis. When I was pursuing my masters in France, to do medical image analysis we were based in a hospital. We helped cardiologists and by using MRI images of the heart, we can detect heart attacks. I built tools to quantify infarct, so we quantified how many percent of the cardiac muscle cells are already dead. From there, the doctors can determine the next steps. After six months, we will assess it again, how many percent is the infarct? There are also different kinds of infarct, for example after the heart attack happens, can the cardiac muscle cells be restored or are they already dead. So that's the interesting part when I was pursuing my masters. When I was doing my PhD, I focused on whole-body MRI. From MRI scans that are taken from the neck to the knees, we can detect fifteen different organs. We just used AI, we used machine learning methods that we created. From there it will lead to pathology, so if for example there is an abnormality, like in the liver there is a tumor, well it can be found out. Because we already have standards on what a normal liver is like.

**G:** I see, so you can find out about it when there's even a little bit of a difference, right?

**V:** Yes. I also did population study from Biobank in the UK.

**K:** Okay, let's shift a bit to a topic about your education. This is actually Galuh's question, I know that she wrote this question, so maybe she wants to ask this one.

**G:** Usually after we're done with our undergraduate studies... a lot of my friends too are also wondering whether to jump to the industry of pursue higher education first. What was your consideration when you decided to choose to pursue your masters and then PhD?

**V:** Actually, when I graduated from S1, I worked for a while, but I was bored being in Jakarta. I wanted something different. But actually, I've always wanted to be a lecturer, academician... I like research. And working got me bored, so I decided to pursue a masters degree while also traveling at the same time. We had this program at that time called Erasmus Mundus from the European Union, so we studied in  three different countries, in the UK in Scotland, then in Spain in Barcelona, in Catalunya, then in France in Bourgogne. And we also learned the culture, so we got the knowledge and the traveling as well. Then for my PhD, I went on a hiatus for some time to focus on my families, and then I continued because I like research, I want to be an academic. I started my PhD in 2015.

**K:** So now you've graduated?

**V:** I've graduated, alhamdulillah.

**K:** Congratulations! How did you find out about the (Erasmus Mundus) program?

**V:** If you browse scholarship websites often, you can see the info about the program. I think it still exists, right? Erasmus Mundus?

**G:** It still exists... but isn't each year they can have a different topic, so...

**V:** Yes, but for Masters degree, you can also apply for the university first and later the scholarship. Depends on each person's interests.

**G:** Now that the application season is starting, many applications are starting to open... for our listeners who are applying as well, do you have any tips on how to make your application stand out—be it when you're applying for universities or scholarships?

**V:** First, if you have a good transcript, then make sure to highlight that. For example, our GPA is 4... aside of the transcript, also highlight your motivation letter. It's better that you also give personal motivations or personal experiences that align with the project that you're working on or the major that you're going to take. For example, why are you interested in the major that you're taking? Or why are you interested with a specific research? In the motivation letter you also have to write, what do you want to contribute in the future? If you apply to many scholarships or universities, personalize each application. Adjust based on the major, the topic, the scholarship... it needs effort. If you've failed, try again, don't give up. When I was applying for master's degree I received a number of scholarships, I got rejected too, and for my PhD application I made almost 200 applications during the two years that I was taking care of my kid. But that's okay, because of that I got to read a lot of research.

**G:** The more often you apply the better each of your application will be...

**V:** But yeah, don't give up.

**K:** Between your master's and PhD you were on hiatus for quite a while, did you also work during that time?

**V:** During that time... I was waiting for my husband in the Netherlands, so I was doing my own projects, I wrote a book while also making some albums... there were quite a few albums.

**K:** From your profile it seems like you have it all—family, careers...

**G:** Passion projects...

**K:** How can you have it all like that? Are there any tips and tricks to manage all those?

**V:** Maybe the first one is to set your priorities. For now, family is my number one priority, and the others have to adjust. For example, for work I... work on research that can be more flexible, but sometimes I go to the office too, but after I pick up my kind from school I continue my work at home. In London, I don't have anyone helping me out—no family helping me out, I mean after I get home I have to clean up, cook by myself, drop and pick up my kids... actually I have to manage my energy as well, because otherwise I'd get exhausted. After setting priorities, we also have to enjoy doing all those. Because if you don't, well... for music, music is my hobby so that I don't get stressed out.

**G:** That's important.

**K:** You also seem to really prioritize your family, I'm curious, what does family mean to you?

**V:** Family is my top priority, they're the ones who really support me. When I was doing my PhD they were also with me and now we're all still in London. They're my number one supporters and we support each other.

**K:** What about music?

**V:** I've always liked composing my own music and we also do home recording at home. So we create the music ourselves using laptops, digital audio workstation, audio interface, mixing, mastering...

**K:** You do it all yourself?

**V:** Yes, everything—singing, recording, playing violin, piano, guitar... but now it's more of my oldest child's hobby, doing video covers... singing on YouTube.

**G:** So it's the family's hobby...

**V:** More of like the oldest child's.

**K:** Okay, so thank you so much Vanya for the conversation, and thank you also for Vanya's little kid for coming along with us!