---
title: cl7
permalink: /cl7/
variant: markdown
description: ""
third_nav_title: 华文
---
<style>
.entry-title{
  font-size: 2.25rem;
  font-weight: 700;
  margin-bottom: 2rem;
  text-align: center;
}
.entry-content p{
  text-align: justify;
}

.entry-title.supported-by{
  margin-bottom: 0;
  margin-top: 3rem;
}

.entry-content .buttons-container{
  align-items: center;
  column-gap: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.entry-content .buttons-container .btn-link{
  background-color: #7431e8;
  border-radius: 0.4rem;
  color: #fff;
  font-size: 1.5rem;
  margin-bottom: 1rem;
  padding: 15px 20px;
  text-align: center;
  text-decoration: none;
  width: 15rem;
}
.entry-content .buttons-container .btn-link:hover{
  background-color: lightgrey;
}

.entry-content.sharing-sessions{
  align-items: center;
  display: flex;
  flex-direction: column;
  row-gap: 1.5rem;
}
.entry-content.sharing-sessions .session-item{
  align-items: flex-start;
  background-color:#d84178;
  border-radius: 0.5rem;
  color: #ffffff;
  row-gap: 2rem;
  display: flex;
  font-size: 1.1rem;
  flex-direction: column;
  line-height: 1.2;
  justify-content: space-between;
  margin-bottom: 2rem;
  padding: 1rem;
  width: 100%;
}
.entry-content.sharing-sessions .session-item .lower-wrapper{
  display: flex;
  flex-direction: column;
  row-gap: 2rem;
  width: 100%;
}
.entry-content.sharing-sessions .session-item .session-link{
  border: 2px solid lightgrey;
  border-radius: 0.5rem;
  padding: 1rem;
  text-align: center;
}
.entry-content.sharing-sessions .session-item .session-link a{
  color: #ffffff;
}

.entry-content.sharing-sessions.malay-sessions .session-item{
  background-color: #a3c864;
}

.entry-content.sharing-sessions.tamil-sessions .session-item,
.entry-content.sharing-sessions.preschools-exhibitors .session-item{
  background-color: #9b4490;
}

.entry-content.sharing-sessions.english-sessions .session-item{
  background-color: #fa0;
}

.entry-content.sharing-sessions.primary-secondary-exhibitors .session-item{
  background-color: #a3c864;
}

.entry-content.sharing-sessions .session-item .session-link:hover{
  background-color: lightgrey;
}

.entry-content.sharing-session-item{
  font-size: 1.2rem;
}
.entry-content.sharing-session-item .sharing-sessions-nav{
  align-items: center;
  column-gap: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding-bottom: 1rem;
}
.entry-content.sharing-session-item .sharing-sessions-nav .inner-nav-wrapper{
  column-gap: 1rem;
  display: flex;
  flex: 2;
  flex-wrap: wrap;
  justify-content: flex-end;
  row-gap: 1rem;
}
.entry-content.sharing-session-item .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
  background-color: #d84178;
  border-radius: 1rem;
  color: #fff;
  padding: 1rem 2rem;
  text-align: center;
  width: 100%;
}
.entry-content.sharing-session-item.malay-session .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
  background-color: #a3c864;
}
.entry-content.sharing-session-item.tamil-session .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
  background-color: #9b4490;
}
.entry-content.sharing-session-item.english-session .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
  background-color: #fa0;
}
.entry-content.sharing-session-item .sharing-sessions-nav .inner-nav-wrapper .nav-btn:hover{
  background-color: lightgrey;
}
.entry-content.sharing-session-item .profile-photo-container{
  align-items: center;
  column-gap: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  row-gap: 1rem;
}
.entry-content.sharing-session-item .profile-photo{
  align-items: center;
  column-gap: 2rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  row-gap: 2rem;
  margin-bottom: 2rem;
}
.entry-content.sharing-session-item .profile-photo img{
  border-radius: 100px;
  width: 200px;
}
.entry-content.sharing-session-item.awardee-item .profile-photo{
  width: 100%;
}
.entry-content.sharing-session-item .profile-name{
  font-weight: 700;
  margin-bottom: 3rem;
}
.entry-content.sharing-session-item h4{
  color: #d84178;
}
.entry-content.sharing-session-item.malay-session h4{
  color: #a3c864;
}
.entry-content.sharing-session-item.tamil-session h4{
  color: #9b4490;
}
.entry-content.sharing-session-item.english-session h4{
  color: #fa0;
}
.entry-content.sharing-session-item.awardee-item h3,
.entry-content.sharing-session-item.awardee-item h4{
  color: #4372d6;
}
.entry-content.sharing-session-item .section-wrapper{
  margin-bottom: 3rem;
}

.entry-content.awardees-container h4{
  font-weight: 700;
  margin-bottom: 3rem;
}
.entry-content.awardees-container a{
  text-decoration: none;
}
.entry-content.awardees-container .section-wrapper{
  margin-bottom: 10rem;
}
.entry-content.awardees-container .section-row{
  column-gap: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  row-gap: 1rem;
}
.entry-content.awardees-container .section-column{
  width: 30%;
}
.entry-content.awardees-container .awardee-wrapper{
  align-items: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  row-gap: 1rem;
}
.entry-content.awardees-container .awardee-wrapper .awardee-pic{
  width: 10rem;
}
.entry-content.awardees-container .awardee-wrapper .awardee-profile{
  color: #484848;
  text-align: center;
}
.entry-content.awardees-container .awardee-wrapper .name-english{
  font-size: 1.25rem;
  margin-bottom: 1rem;
}
.entry-content.awardees-container .awardee-wrapper .name-chinese{
  font-size: 1.25rem;
  margin-bottom: 1rem;
}

.entry-content .btntop{
  position: fixed;
  float: right;
  bottom: 20px;
  right: 80px;
  z-index: 99;
  boder: none;
  background-color: #3bb9ff;
  cursor: pointer;
  padding: 15px;
  boder-radius: 4px;
  color: #fff;
  font-weight: 600;
}

.coming-soon{
  color: #7431e8;
  font-size: 2rem;
  font-weight: 700;
  margin-top: 3rem;
  text-align: center;
}

@media all and (min-width: 40rem ){
  .entry-content.sharing-sessions{
    align-items: flex-start;
    display: flex;
    flex-direction: column;
    row-gap: 1.5rem;
  }

  
  .entry-content.sharing-sessions .session-item .lower-wrapper{
    align-items: center;
    flex-direction: row;
    justify-content: space-between;
  }

  .entry-content.sharing-session-item .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
    width: 45%;
  }
}
</style>

<div class="entry-content sharing-session-item">
<div class="sharing-sessions-nav">
<a href="/sharing-and-workshops/sharing-sessions/chinese-sessions/">Back</a>
<div class="inner-nav-wrapper">
<a class="nav-btn" href="#C1">View Speaker's profile here</a>
<a class="nav-btn" href="#C2">View Synopsis here</a>
</div>
</div>

<div class="profile-photo">
<img alt="Lu Xiaoyan" src="/images/Sharing_sessions/lu-xiaoyan.jpg">
<img alt="Liao Sulian" src="/images/Sharing_sessions/liao-sulian.jpg">
</div>

<div class="profile-name">
Ms Lu Xiaoyan<br>
陆小燕老师<br>
华文主导老师<br>
职总优儿学府幼乐园<br>
<br>
Ms Liao Sulian<br>
廖素莲老师<br>
华文主导老师<br>
职总优儿学府幼乐园
</div>

<div class="section-wrapper">
<h4 id="C1">讲者介绍</h4>
<p>
陆小燕老师在幼教领域已有超过12年的教学经验，目前在职总优儿学府幼乐园担任华文主导老师，并曾荣获2022年杰出学前母语教师奖。她还担任了2023年学前华文教师研讨会工作坊的讲员。陆老师认为，对新加坡的幼儿来说，使用华文学习数学不仅有助于他们的数学学习，还可以促进他们的语言发展和文化认同。她强调老师和家长可以通过有趣的活动和不同的学习方式，帮助幼儿在愉快的氛围中学好华语，并培养他们对华文的兴趣和使用华文的自信。
</p>
<p>
廖素莲老师在幼教领域拥有十年的丰富工作经验，目前担任职总优儿学府幼乐园的华文主导老师。她曾荣获2021年杰出学前母语教师奖，并在2023年学前华文教师研讨会上担任工作坊讲员。廖老师认为语言的学习应融入日常生活，成为生活化的语言，这样语言才能活跃起来。因此，她特别重视并鼓励幼儿在日常生活中积极使用华语，让华语成为孩子们生活中用得自然，用得自信的语言。
</p>
</div>

<div class="section-wrapper">
<h4>Profile</h4>
<p>
Ms. Lu Xiaoyan, has over twelve years of experience in Early Childhood Education, and currently holds the position of Chinese Lead teacher at My First Skool. She was awarded the Outstanding Preschool Mother Tongue Teacher Award in 2022. In 2023, she was a speaker at the Preschool Chinese Teachers' Seminar Workshop.
</p>
<p>
Ms Lu advocates  the integration of numeracy concepts into the learning of  Chinese as this not only enhances preschoolers' mathematical learning but also supports their language development and cultural identity. She believes that teachers and parents should foster children's Chinese language learning in a joyful environment through engaging activities and diverse learning approaches that nurture their interest and confidence in the language.
</p>
<p>
Ms Liao Sulian has ten years of experience in Early Childhood Education and is currently the Lead Chinese teacher at My First Skool. She was awarded the Outstanding Preschool Mother Tongue Teacher Award in 2021. She also conducted a sharing session at the 2023 Preschool Chinese Teachers Seminar.
</p>
</div>

<div class="section-wrapper">
<h4 id="C2">工作坊内容简介</h4> 
<p>
兴趣，是幼儿学习华文的动力。丰富有趣的华文游戏能够激发幼儿主动、轻松自然地学习华文。本次分享会主要是针对在活动中融入数学元素，让幼儿通过在儿歌、手指谣、绘本、美劳、音乐等活动一边学习华文，一边培养数学概念。家长能从分享中学习到华文教学策略，也可以通过现场与讲员的互动，学习一些能在家中和幼儿进行的有趣华文数学游戏，从而通过数学游戏激发幼儿对华文的兴趣。
</p>
</div>

<div class="section-wrapper">
<h4>Synopsis</h4> 
<p>
Children's learning of Chinese is built upon interest. Engaging and enjoyable Chinese games can inspire children to learn Chinese actively and naturally. This sharing session integrates mathematical elements into activities such as nursery rhymes, finger rhymes, picture books, art and craft, music and materials so as to cultivate early mathematical concepts in children. During this sharing session, participants will learn positive Chinese teaching strategies through interaction with the speakers. Parents will also take away interesting Chinese mathematical game ideas for playing with their children at home.
</p>
</div>

<div class="section-wrapper">
</div>
</div>