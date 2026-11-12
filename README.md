# Echoo publishing skill · سكل النشر عبر Echoo

**English** · [العربية](#العربية)

A **skill** is a page of instructions that an AI agent (ChatGPT, Claude, …) reads to learn how to do a job properly.
This one teaches an agent how to use **Echoo**'s MCP server to prepare picture posts, stories and reels (videos) for your Facebook Pages and Instagram accounts and publish them **only after you approve in the chat**.

[`SKILL.md`](SKILL.md) is the skill. It covers: how to connect, the rules that never bend (approval first, honest results, no tokens), every tool, the step-by-step workflow, times and limits, pictures and videos (including Instagram's shape limits and the AI label), stories and reels, captions, how to read every result and error, and example conversations.

## How to use it

1. Have an Echoo account with your Page connected, and add your Echoo MCP address to your AI app as a custom connector (the address is shown in your Echoo dashboard; sign in with OAuth when asked).
2. In a new chat, send the agent this link and one sentence:

   ```
   https://raw.githubusercontent.com/mustafambusiness-maker/echoo-skill/main/SKILL.md
   Read this and follow it whenever I ask you to publish with Echoo.
   ```

   (In Arabic: «اقرأ هذا الرابط وطبّقه كلما طلبتُ منك النشر عبر Echoo».)
3. Ask for what you want: *"Make a poster for my shop and publish it now"*, or *"make 10 posts for this week's offers and spread them between 10 am and 9 pm"*.

In **Claude**, you can also add the file as a Skill: put it in a folder named `echoo-publishing` as `SKILL.md`.

## What it does not do

- It holds **no secret**. Your agent never receives your Meta tokens or passwords; Echoo keeps them.
- It cannot switch real publishing on, change the limits, or bypass your approval. Those belong to the account owner and to Echoo's server.
- It is not a replacement for reading Meta's rules: you remain responsible for what you publish.

This repository is not affiliated with Meta, OpenAI or Anthropic. Licensed under the MIT License.

---

## العربية

**السكل (Skill)** صفحة تعليمات يقرؤها المساعد الذكي (ChatGPT أو Claude أو غيرهما) ليتعلّم كيف ينجز عملًا بشكل صحيح.
هذا السكل يعلّم المساعد كيف يستعمل خادم **Echoo** (MCP) ليجهّز منشورات بالصور وستوري وريلز (فيديو) لصفحاتك على فيسبوك وحساباتك على إنستغرام، وينشرها **فقط بعد موافقتك داخل المحادثة**.

الملف [`SKILL.md`](SKILL.md) هو السكل. فيه: طريقة الربط، والقواعد التي لا تُكسر (الموافقة أولًا، والصدق في النتائج، وعدم طلب الرموز)، وكل أداة، وخطوات العمل، والأوقات والحدود، والصور والفيديو (وحدود شكل الصورة في إنستغرام وعلامة الذكاء الاصطناعي)، والستوري والريلز، والنصوص، وكيف يقرأ كل نتيجة وخطأ، وأمثلة محادثات.

### كيف تستعمله

1. عندك حساب في Echoo وصفحتك مربوطة، وأضفتَ عنوان MCP الخاص بـ Echoo إلى تطبيق الذكاء الاصطناعي كموصل مخصص (العنوان يظهر في لوحة Echoo، وسجّل الدخول بـ OAuth عند الطلب).
2. في محادثة جديدة أرسل للمساعد هذا الرابط وجملة واحدة:

   ```
   https://raw.githubusercontent.com/mustafambusiness-maker/echoo-skill/main/SKILL.md
   اقرأ هذا الرابط وطبّقه كلما طلبتُ منك النشر عبر Echoo.
   ```

3. اطلب ما تريد: «سوِّ بوستر لمتجري وانشره الآن»، أو «سوِّ 10 بوستات لعروض الأسبوع ووزّعها من 10 صباحًا إلى 9 مساءً».

في **Claude** تستطيع أيضًا إضافة الملف كسكل: ضعه في مجلد اسمه `echoo-publishing` باسم `SKILL.md`.

### ما لا يفعله

- لا يحتوي **أي سرّ**. المساعد لا يستلم رموز Meta ولا كلمات المرور، فـ Echoo هو من يحفظها.
- لا يستطيع تشغيل النشر الحقيقي ولا تغيير الحدود ولا تجاوز موافقتك. هذه بيد صاحب الحساب وخادم Echoo.
- لا يغني عن قراءة قواعد Meta: أنت المسؤول عمّا تنشره.

هذا المستودع غير تابع لـ Meta ولا OpenAI ولا Anthropic. الترخيص: MIT.
