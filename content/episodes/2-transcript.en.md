+++
date = "2019-05-12"
description = "Transcript for Episode 2 of Kartini Teknologi with Asanilta Fahda."
linktitle = ""
title = "Transcript - Episode 2 - Asanilta Fahda"
slug = "2/transcript"
type = "transcript"
+++

**Kiki (K):** Hi everyone, welcome back to Kartini Teknologi with Kiki and Galuh.

**Galuh (G):** Hello!

**K:** Today we'll be talking about something that we have just done... probably around three weeks ago... the presidential election! Or actually the general elections, but we'll specifically talk about the presidential election. Anyway. About this presidential election, we already have one special guest, Asanilta Fahda.

**G:** So Asanilta is a graduate of ITB. She's a former software engineer in Shopee Singapore in the Natural Language Processing team, and she's also the initiator and coordinator of a website that...

**K:** That is so famous.

**G:** ... and that we probably have used before the presidential election, PilahPilihPilpres.

**K:** Yes, Nilta could you please introduce yourself, what's your background, where you come from, your hobbies?

**Nilta (N):** Hi, my name is Nilta and I'm from Informatics ITB year 2013. After graduating from ITB, I worked at [Prosa.ai](http://prosa.ai) for a while and then I worked at Shopee Singapore. Now I'm back in Indonesia. As for hobbies, I'm into art such as music and drawing.

**K:** Ah you both like drawing!

**G:** Yay!

A: But I'm not that good at it.

**K:** If we take a look at your profile it seems like you really enjoyed dabbling in NLP. Could you tell us how you got interested in NLP?

**G:** Or maybe you can begin with what NLP is actually?

**N:** Okay, so NLP is short for *natural language processing*. In Indonesian it's called *"pemrosesan bahasa alami"*. NLP is a field that connects natural language, which is a language spoken by humans like Indonesian, English... connected to computers. So we can program and train computers to capture information spoken in natural language or written in natural language. The result can give added value for humans, such as Google Translate or Siri... those are all applications of NLP.

**K:** That's interesting. So how did you get interested in the field? Can you tell us a bit more about that?

**N:** Ever since I was little I've loved languages. I love learning languages because it's interesting to see the similarities and differences between languages and to learn how language can represent our thoughts. And... the development of languages, such as in Indonesian we have the formal language but we also have our slang language that isn't really documented. They're all so interesting and they also contain a lot of information within them.

**K:** So ever since you were a kid you've loved languages. Do you have any specific reason on why you ended up choosing NLP? I mean, if you love languages since you were a kid you can also choose a language major, perhaps literature? Why did you choose IT and focus on NLP?

**N:** When I was a kid I also loved playing computers and sometimes I thought, wow, it would be cool if I can build this, make that... it all seems so magical. That's why I thought about getting into the IT field. And that's also why it's so fascinating for me that we can combine IT with other fields that are of our interests as well.

**G:** So the combination of IT and languages, which is NLP, seems to suit your interests perfectly. If I take a look at your experiences, you were an intern at Japan Advanced Institute of Science and Technology. Can you tell us about what project you worked on there?

**N:** In Japan I was first introduced to deep learning, which is one of the subfields of machine learning. Because I was just getting started I was given a task that is pretty simple, which is doing sentiment analysis of Amazon reviews. So I categorized which reviews are positive and which ones are negative. As for the classification method, I experimented with various methods such as CNN and LSTM. I started off with LSTM, but then someone suggested CNN to me. I also tried to see, if I do pre-processing then how the result would be... and if I use which word embedding what the result would be. I used Python and Keras as the library. So it wasn't that complex.

**G:** From the experiments there was a wide range of configurations that you tried as well. Which methodology was the best for the case that you worked on?

**N:** I don't remember the specifics, I think it involved two steps... combining CNN and LSTM. And it seems that when I removed the stopwords the result was worse. I don't really remember the specifics because there were a lot parameters. After the project, I also had another project with Prosa.ai. I created a text normalizer for slang Indonesian to formal Indonesian. It was to be used to process the next analytical steps because to talk about the same thing, such as the word *"nggak"* ("no" in Indonesian), we can write "ngga", "g", and so on... so we have to normalize it. Initially I used rule-based but then I switched to sequence to sequence deep learning. However it required a lot of data.

**G:** Where did you get the data from? Because to accomplish that you would need something other than formal texts right?

**N:** So at [Prosa.ai](http://prosa.ai) we had another team that labels the data. We obtained the data from Twitter and we labeled them on our own. That's the data that we use for training data.

**K:** So it's still manual right?

**N:** Yes, and for NLP if we want to use machine learning we need a lot of clean data.

**K:** Is there an existing dataset somewhere? Or is there none so you need to obtain them yourself?

**N:** That's always the biggest problem of NLP for Indonesian—the data is very rare.

**K:** Ah, still limited.

**N:** Yeah. When it comes to English there is a lot of data though.

**K:** Okay, so we talked about your internship. You also worked at Shopee handling NLP as well, right?

**N:** Yes.

**K:** Can you tell us more about it, in Shopee did you handle NLP for English or Indonesian?

**N:** I was responsible for Shopee Indonesia. But actually in Shopee there are a lot of languages, there are Indonesian, English, Mandarin, Vietnamese, Thailand. There are algorithms that can be applied generally to all languages, but there are also those that need to be adjusted per language.

**K:** So you combine the algorithms?

**N:** It depends because for each country there can be differences, there can be similarities as well. And the language in the e-commerce domain can be different with our day-to-day language. For example in e-commerce there is a mix of Indonesian and English, and the order can be arbitrary... so the characteristics and the ways to handle it can be different.

**K:** I see. So you've been working with NLP for written text right, not verbal?

**N:** Yeah.

**K:** I see. What do you think are the challenges of doing NLP especially for Indonesian?

**N:** The data is very limited, and the basic tools are so-so. For example, in English we already have a POS tagger with a 90-something percent accuracy that we can use immediately.

**K:** What's a POS tagger?

**N:** POS tagger is short of part-of-speech tagger. So if we have a sentence, using POS tagger we can tag every word in the sentence as verb, noun, adjective and so on... and those can be important information for other processes on top of it. When I was doing my thesis I worked on a spelling and grammar checker which utilized POS tagger as well. But if the POS tagger itself isn't that good, that can affect the accuracy of the system on top of it.

**K:** So POS tagger is like some kind of identifier?

**N:** Yeah... for kinds of words. But that's just one of the examples, there is a lack of resources especially that we have two versions of Indonesian—formal and non-formal—that are like two different languages.

**K:** Aside of that, do we already have a lot of experts on NLP?

**N:** There are probably not many yet... the person that I know works on NLP the most is my own thesis supervisor, Ms. Ayu. She also created Prosa.ai. So Prosa.ai's specialty is NLP.

**K:** But lately I've been seeing startups that... are getting more focused...

**N:** Like [Kata.ai](http://kata.ai) and the likes.

**K:** Yes, more focused to machine learning, AI, and such. But yeah there probably aren't a lot of experts in Indonesia yet.

**N:** Perhaps in terms of academic there aren't many yet. But fortunately there are a lot of developments on businesses that are creating startups in the field of AI, NLP, and such.

**K:** Anyway, something came to my mind when you said that there is a lack of resources for Indonesian. Have you heard of a project called Common Voice? It's Mozilla's but it's more like speech. Have you heard about it?

**N:** I haven't, but seems interesting. What's that?

**K:** Yeah... so Common Voice is our project, we had this problem when we were working on Firefox OS. So Mozilla once created a mobile OS called Firefox OS. We wanted to create something like Siri, OK Google... but our problem was, there weren't a lot of speech data. It was too expensive to purchase them too. We were then inspired to crowdsource it, so we created a project called Common Voice to collect voices of each language from many languages. For now we have English with the most voices, but we're starting to have German... we're also starting to have Indonesian but there aren't many yet, we haven't opened the voice contribution yet. So in Common Voice there is a sentence and we have to speak that sentence... the sentence will then be stored. Well first it would be reviewed together and then stored and opened to the public. So if someone wants to develop machine learning for speech they can also use the data from Common Voice.

**N:** That's interesting, crowdsourcing the data.

**K:** Yep.

**G:** If you're bored with written texts maybe you can play around with speech using Mozilla's Common Voice.

**N:** Yeah, actually a lot of my friends work in speech too. I don't have experiences in it but I think both are very interesting.

**K:** Have you tried it though?

**N:** I haven't except for when I was in college I think. To me speech is more technical because when it comes to speech you have to look at the soundwave and stuff so...

**K:** More complex?

**N:** Yeah, more complex to me. Which is why I like text better.

**K:** Is there any difference between speech and text, aside of what you said about soundwave? Is there any other difference between NLP for speech and text?

**N:** The way of processing them is going to be different, though the algorithms are similar such as when you're using machine learning. With written texts, for example, the pre-processing step can be something like removing stopwords. In speech, the pre-processing is probably going to involve something else... perhaps removing noise or something. I'm not so sure though.

**K:** Talking about tech stack, is there any special tech stack if we want to learn NLP? What is the tech stack that is usually used to process the big data or the data itself?

**N:** In Shopee I use Go. To process the big data I use Hadoop, MapReduce. So we usually program MapReduce jobs that produce something. Outside of Shopee for NLP I usually use Python, and for deep learning I usually use Keras.

**K:** Okay. Did you learn big data processing from when you were in college or...?

**N:** When it comes to big data processing, I actually learned it when I was at Shopee because in college I didn't take the classes. There was a distributed systems class for example. I kind of regret that I didn't take it. Fortunately in Shopee my boss and my friends kindly taught me.

**K:** How did you learn, did you learn by yourself or did you learn by solving challenges you came across at work or maybe something else?

**N:** Sometimes I like learning by myself, such as learning in online courses.

**K:** Where did you take these online courses?

**N:** I mostly took them in Udemy because it was reimbursed by my office. Aside of Udemy I also learned through Coursera courses. There are a lot of resources in YouTube as well, free resources that explain you through some topic. But yeah... usually it's easier to imagine it when we try our hands at it, finding the solutions to the problem that we've been given.

**K:** Yeah that's true, we usually understand something when we have implemented it isn't it? Okay... now let's move on to PilahPilihPilpres. Can you tell us a little bit about how the entire process of the project was, starting from shaping the team, having discussion with the team, and finally launching the website itself? I think you launched it a week before the elections right?

**N:** It's two days before actually, we didn't have a lot of time. I just thought of the idea two weeks before the elections. I read my friend's tweet... they said that they didn't want to vote because they didn't follow the news about both pairs of candidates. It was kind of difficult to catch up on them, with the rumor mills. So to make something that is objective and can summarize everything I thought of making something that is also fun, like BuzzFeed quizzes. I formed the team by asking my friends on Twitter, "does anyone want to help?" and thankfully I got friends that were knowledgeable in politics: Fikri Khalqih, Eduard Lazarus, and Audhina Nur Afifah. That's the politics team. For tech, initially I was going to do it but because I had to help out my parents and sibling in Kalimantan, I gave the responsibility to my friend, Feryandi. He created the web. So I actually just gave the idea, coordinated a bit, and helped to spread the news about it, to help making it viral. Luckily it went viral on its own.

**G:** So it took you all two weeks to make it?

**N:** The creation process was just a week, for the first week I was looking for people and creating the group and everything, and we created it just a week before...

**G:** So all the content and the web app in just a week?

**N:** Yep.

**G:** Wow that's so cool!

**N:** Fortunately the people in my team are ambitious.

**G:** What are the challenges that you all faced when making PilahPilihPilpres, aside of time for sure because you did only have a week after all. Are there other challenges?

**N:** The main challenge is actually from content. From the politics side, it was difficult to find the clear stance of each pair of candidates. It could be grey and inconsistent, the first time they might say A but later they might say B. We couldn't include that as our content. From the technical side, actually during the creation process we didn't come across any challenge because Fery did finish it quickly. However after we launched the site, it was accessed by half a million people and that was when we realized that there are a lot of things that we could fix that we didn't think of before. Feryandi also wrote an article about that on his Medium by the way. You can check it at medium.com/@feryandi.

**K:** Wow that's so cool. Do you have any plan on developing it further?

**N:** Actually we think that if we want to develop it further we would make it to be more in-depth, not just the presidential elections but also for parties and legislatives as well. But to do so we would need to have more resources and of course we would need funding as well.

**G:** Do you have anything else that you want to tell us about PilahPilihPilpres?

**K:** Such as where the name comes from probably?

**N:** It's actually an idea from my friend. I told them about the idea and they asked me what the name is and that was a few days before the presidential election. Before the launch, I was like, oh we need a name? I was thinking something like Kuis Pilpres 2019 but it wasn't that catchy so they gave me that idea.

**K:** I see. It's a nice name, it kinda has a rhyme to it. PilahPilihPilpres. Okay, let's talk about something else. So you just resigned from Shopee. Can you tell us a bit about why you decided to resign?

**N:** It was just a personal problem, not because of the company or anything. I just wasn't happy living in Singapore alone. I wasn't happy and got stressed. So I thought, well, a year was enough for me to learn, gain experiences, save up some money, so now I'm back. I'm hoping that I can be more useful for Indonesia as well.

**K:** So you were there for a year?

**N:** Yeah more or less a year.

**K:** Was that your first time living away from home?

**N:** Actually when I was in high school I went on an exchange for a year to Belgium. But because I was living with host family and I went to school as well, there were a lot of friends... it just felt different from the work environment. Especially when you're living alone in Singapore which is kind of... known for its harsh work life. I mean most people in Singapore just go to work, well probably not all are like that but I just didn't feel excited, monotonous, just going to work and then going home.

**K:** But there were a lot of Indonesians there though, right?

**N:** There were some. No women, though. There was one but she came right before I left. We do really need more Indonesian women.

**K:** I agree. When I worked at a startup I was the first woman to join the product, engineering team. Everyone else was a man. After I was there, a few months later there was another woman. So yeah we need more women. I also took a look at your SoundCloud and I saw that you wrote songs as well and I was like, wow. Do you have any plan on merging both of your interests in music and technology?

**N:** Actually the combination of both music and technology has a lot of potentials. There are a lot of possibilities. I actually have a few ideas but since they're still plans I'll keep them a secret. Hopefully I can turn them into my personal projects especially now that I'm not that busy. When I'm busy working I usually don't have time for working on personal projects or even playing music. It's also why I have been on hiatus for a long time.

**K:** Do you have any project that you're currently working on?

**N:** For now not really, I just got back from vacation and now I want to take a break. I'm mostly studying things now.

**K:** All right, so aside of NLP and music, you also have interest in social issues. In Indonesia, what do you think are the social issues that haven't involved technology or actually can be improved with technology, or maybe we already have the implementations but they're not optimal yet. Do you have any plans or ideas that you want to work on regarding that?

**N:** There are a lot of potentials on that actually and yesterday my sibling did give me an idea. This is more about politics because they are in politics. People usually send their aspirations for their representatives through social media, WhatsApp, text messages... and sometimes not all of them are replied to and not all of them can be read. We can have a system that classifies them, for example, this person's aspiration is about education or flooding or something else. And from the text we can... categorize and store the data... for example we have a scholarship program for 1000 people. From the system we can retrieve the people who have sent their aspiration regarding scholarships... for example, A has asked for scholarships before or something like that. It's interesting, there are lots of applications.

**K:** Is it something like Qlue?

**N:** What's Qlue?

**K:** The Qlue application, I'm not sure it's probably in Jakarta only perhaps? So we can also give feedback, for example I have complaints regarding flooding, we can send our complain through the Qlue app.

**N:** I haven't tried it, I was thinking that this is for people who send their aspirations to the representatives in their region. Mostly they send it through Facebook message or an aspiration hotline in WhatsApp. Maybe they don't know about other applications.

**G:** That's true though, even if I have a lot of aspirations I sometimes don't know where to send them, I'm not sure if they have their own hotline or WhatsApp or something, and if I don't know I get lazy to report something. So if the system is clear like what Nilta said I think it's really cool and because people of the system people believe that the messages will be read by their representatives they can get encouraged to send more of their aspirations.

**K:** Especially if the aspirations are displayed in public, so we can be accountable for each other, for example if Galuh complains something about this, and other people complain about it too... we can know what other people think about the current government. It'd be cool of this comes true.

**G:** Yep I'd love that. When all aspirations are public, if a representative does not implement it, they would have no reason to say "no one's ever told me that".

**K:** Nilta, do you have any last words?

**N:** From me, for everyone who has an interest in the technology field, now you can combine technology with your other interests no matter what they are, such as language, music, politics, and others. We all can get added value from technology. Most importantly we have to analyze its benefits well.

**K:** That's right. I used to have a lot of interests actually, I loved writing, looking at nice buildings, I wanted to be an architect. But I end up in technology. I don't think there's any loss in learning about technology because it's a field that you can combine with other fields. So if you have interests in fields such as the creative field, art... well that's probably the same, or fields such as politics like what we talked about. The knowledge is more... universal.

**K:** So that's our conversation with Asanilta. How do people call you, it's just Nilta right?

**N:** Just Nilta. Most people get Asanilta wrong.

**K:** Oh really? What's the meaning of Nilta?

**N:** Nilta means "Nilai Tambah" (*"added value"* in Indonesian). So the hope is to become an added value haha.

**K:** I see, I didn't know that before, I thought it's from another language or something. So that's our conversation with Nilta. Thank you so much for the knowledge that you've shared with us. Hopefully you can come back to Kartini Teknologi in the future. If in the future you have new projects that you're working on maybe share them with us and we can discuss about them later. Thank you so much Nilta.

**N:** Thank you Kiki and Galuh.

**G:** Thank you!

**K:** Thank you, bye!