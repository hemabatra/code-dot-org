---

title: <%= hoc_s(:title_how_to) %>
layout: wide
nav: how_to_nav

---

<%= view :signup_button %>

# Kodlama Zamanını nasıl öğretirsiniz

Join the movement and introduce a group of students to their first hour of computer science with these steps:

## 1) Bu "Nasıl Yapılır" videosunu izle <iframe width="500" height="255" src="//www.youtube.com/embed/SrnvvWDm73k" frameborder="0" allowfullscreen></iframe>
## 2) Choose a tutorial for your hour:

We provide a variety of [fun, hour-long tutorials](<%= resolve_url('/learn') %>) for students of all ages, created by a variety of partners.

**[Student-guided Hour of Code tutorials:](<%= resolve_url('/learn') %>)**

  * Öğretmenler için çok az hazırlık zamanı gerektirir
  * Kendi yönlendirmelerine sahiptir - öğrencilerin kendi hızlarına ve seviyelerine uygun hareket etmelerine izin verir

**[Teacher-guided Hour of Code tutorials:](<%= resolve_url('https://code.org/educate/teacher-led') %>)**

  * Bazı ders planları ön öğretmen hazırlığı gerektirir
  * Are categorized by grade level *and* by subject area (eg Math, English, etc)

[![](/images/fit-700/tutorials.png)](<%= resolve_url('/learn') %>)

## 3) Kendi Kodlama Saati'nizin tanıtımını yapın

[Bu araçlar ile](<%= resolve_url('/promote') %>) kendi Kodlama Saati'nizi tanıtın ve diğerlerini kendi etkinliklerini düzenlemeleri için teşvik edin.

## 4) Teknolojik ihtiyaçlarınızı planlayın - bilgisayar kullanımı isteğe bağlı

En iyi Kodlama Saati deneyimi internete bağlı olan bilgisayarları içerir. Ama her çocuk için bir bilgisayara ihtiyaç **yok** ve hiç bir bilgisayar olmadan bile Kodlama Saati yapabilirsin.

**Önceden planla!** Etkinlik başlamadan önce aşağıdakileri yapın:

  * Test tutorials on student computers or devices. Make sure they work properly on browsers with sound and video.
  * Provide headphones for your class, or ask students to bring their own, if the tutorial you choose works best with sound.
  * **Yeterli ekipman yok mu?** o halde [ çift programlayı](https://www.youtube.com/watch?v=vgkahOzFH2Q) kullanın. İki kişilik takımlar halinde çalışan öğrenciler birbirlerine yardımcı olurlar ve öğretmene daha az ihtiyaç duyarlar. Ayrıca bu yöntemle öğrenciler bilgisayar biliminin oldukça sosyal olduğunu ve işbirliği gerektirdiğini görmüş olacaklar.
  * **Bant genişliğiniz düşük mü?** Videoları sınıfın ön tarafından izletin, böylece her öğrencinin kendi videosunu indirmesine gerek kalmayacaktır. Ya da internet bağlantısı gerektirmeyen öğreticileri deneyin.

![](/images/fit-350/group_ipad.jpg)

## 5) Start your Hour of Code off with an inspiring speaker or video

**Invite a [local volunteer](https://code.org/volunteer/local) to inspire your students by talking about the breadth of possibilities in computer science.** There are thousands of volunteers around the world ready to help with your Hour of Code. [Use this map](https://code.org/volunteer/local) to find local volunteers who can visit your classroom or join a video chat with your students.

[![](/images/fit-300/volunteer-map.png)](<%= resolve_url('https://code.org/volunteer/local') %>)

**İlham verici bir video gösterin:**

  * The original Code.org launch video, featuring Bill Gates, Mark Zuckerberg, and NBA star Chris Bosh (There are [1 minute](https://www.youtube.com/watch?v=qYZF6oIZtfc), [5 minute](https://www.youtube.com/watch?v=nKIu9yen5nc), and [9 minute](https://www.youtube.com/watch?v=dU1xS07N-FA) versions)
  * [2013 Kodlama Saati başlangıç videosu](https://www.youtube.com/watch?v=FC5FbmsH4fw), ya da <% if @country == 'uk' %> [2015 Kodlama Saati videosu](https://www.youtube.com/watch?v=7L97YMYqLHc) <% else %> [2015 Kodlama Saati videosu](https://www.youtube.com/watch?v=7L97YMYqLHc) <% end %>
  * [President Obama calling on all students to learn computer science](https://www.youtube.com/watch?v=6XvmhE1J9PY)
  * Find more inspirational [resources](<%= resolve_url('https://code.org/inspire') %>) and [videos](https://www.youtube.com/playlist?list=PLzdnOPI1iJNfpD8i4Sx7U0y2MccnrNZuP).

**It’s okay if both you and your students are brand new to computer science. Here are some ideas to introduce your Hour of Code activity:**

  * Explain ways that technology impacts our lives, with examples both boys and girls will care about (Talk about saving lives, helping people, connecting people, etc.).
  * As a class, list things that use code in everyday life.
  * See tips for getting girls interested in computer science [here](<%= resolve_url('https://code.org/girls') %>).

**Need more guidance?** Download this [template lesson plan](/files/EducatorHourofCodeLessonPlanOutline.docx).

**Want more teaching ideas?** Check out [best practices](http://www.slideshare.net/TeachCode/hour-of-code-best-practices-for-successful-educators-51273466) from experienced educators.

## 6) Code!

**Direct students to the activity**

  * Write the tutorial link on a whiteboard. Find the link listed on the [information for your selected tutorial](<%= resolve_url('/learn') %>) under the number of participants.

[col-33]

![](/images/fit-300/group_ar.jpg)

[/col-33]

**When your students come across difficulties it's okay to respond:**

  * “I don’t know. Let’s figure this out together.”
  * “Technology doesn’t always work out the way we want.”
  * “Learning to program is like learning a new language; you won’t be fluent right away.”

**[Check out these teaching tips](http://www.code.org/files/CSTT_IntroducingCS.PDF)**

**What to do if a student finishes early?**

  * Students can see all tutorials and try another Hour of Code activity at [hourofcode.com/learn](<%= resolve_url('/learn') %>)
  * Ya da, erken bitiren öğrencilerden aktiviteyi yapmakta zorlanan diğer arkadaşlarına yardımcı olmalarını rica edin.

[col-33]

![](/images/fit-250/highschoolgirls.jpeg)

[/col-33]

<p style="clear:both">
  &nbsp;
</p>

## 7) Celebrate

[col-33]

![](/images/fit-300/boy-certificate.jpg)

[/col-33]

  * [Print certificates](<%= resolve_url('https://code.org/certificates') %>) for your students.
  * [Print "I did an Hour of Code!"](<%= resolve_url('/promote/resources#stickers') %>) stickers for your students.
  * [Order custom t-shirts](http://blog.code.org/post/132608499493/hour-of-code-shirts-and-more) for your school.
  * Share photos and videos of your Hour of Code event on social media. Use #HourOfCode and @codeorg so we can highlight your success, too!

[col-33]

![](/images/fit-260/highlight-certificates.jpg)

[/col-33]

<p style="clear:both">
  &nbsp;
</p>

## Other Hour of Code resources for educators:

  * Use this [template lesson plan](/files/EducatorHourofCodeLessonPlanOutline.docx) to organize your Hour of Code.
  * Check out [best practices](http://www.slideshare.net/TeachCode/hour-of-code-best-practices-for-successful-educators-51273466) from past Hour of Code teachers. 
  * Watch the recording of our [Educator's Guide to the Hour of Code webinar](https://youtu.be/EJeMeSW2-Mw).
  * [Attend a live Q&A](http://www.eventbrite.com/e/ask-your-final-questions-and-prepare-for-the-2015-hour-of-code-with-codeorg-founder-hadi-partovi-tickets-17987437911) with our founder, Hadi Partovi to prepare for the Hour of Code.
  * Visit the [Hour of Code Teacher Forum](http://forum.code.org/c/plc/hour-of-code) to get advice, insight and support from other educators. <% if @country == 'us' %>
  * Review the [Hour of Code FAQ](https://support.code.org/hc/en-us/categories/200147083-Hour-of-Code). <% end %>

## Kodlama Zamanından sonra ne olacak?

The Hour of Code is just the first step on a journey to learn more about how technology works and how to create software applications. To continue this journey:

  * Encourage students to continue to [learn online](<%= resolve_url('https://code.org/learn/beyond') %>).
  * [Attend](<%= resolve_url('https://code.org/professional-development-workshops') %>) a 1-day, in-person workshop to receive instruction from an experienced computer science facilitator. (US educators only)

<%= view :signup_button %>