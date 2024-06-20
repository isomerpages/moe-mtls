---
title: About Us
permalink: /about-us/
variant: markdown
description: ""
---
<style>
.entry-title{
    font-size: 2.25rem;
    font-weight: 700;
    text-align: center;
  }
  .entry-content p{
    text-align: justify;
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
    background-color:#d84178;
    border-radius: 0.5rem;
    padding: 1rem;
    text-align: left;
    width: 100%;
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
  .entry-content.sharing-sessions .session-item p,
  .entry-content.sharing-sessions .session-item a{
    color: #fff;
    font-size: 1.1rem;
    line-height: 1.2;
  }
  .entry-content.sharing-sessions .session-item:hover{
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
    margin: 0 auto;
    text-align: center;
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
  
  
  @media all and (min-width: 40rem ){
    .entry-content.sharing-sessions{
      align-items: flex-start;
      display: flex;
      flex-direction: column;
      row-gap: 1.5rem;
    }
    .entry-content.sharing-sessions .session-item{
      width: 90%;
    }
  
    .entry-content.sharing-session-item .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
      width: 45%;
    }
  }
</style>

<div class="entry-title">Jointly Organised By</div>

![Ministry of Education, Committee to Promote Chinese Language Learning, Malay Language Learning and Promotion Committee, Tamil Language Learning and Promotion Committee](/images/mtls2024_organised_by.png)

<div class="entry-content">

<p>As of this year, the Mother Tongue Languages Symposium (MTLS) is a biennial event co-organised by the Ministry of Education (MOE), the Committee to Promote Chinese Language Learning (CPCLL), the Malay Language Learning and Promotion Committee (MLLPC) and the Tamil Language Learning and Promotion Committee (TLLPC).</p>

<p>It aims to promote our Mother Tongue Languages (MTLs) by exhibiting good practices and efforts by both schools and the community in the teaching and learning of our respective MTLs. It primarily targets MTL educators from the preschools to lower primary levels and parents with young children.</p>

<p>The theme of this year's MTLS is “Our Mother Tongues as Living Languages”, and the symposium will be held on Saturday, 14 September 2024, at the Suntec Singapore Convention &amp; Exhibition Centre.</p>

</div>

<div class="entry-title">Supported By</div>

![Supported By](/images/mtls2024_supported_by.png)
