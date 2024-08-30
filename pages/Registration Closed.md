---
title: Registration Closed
permalink: /registration/
variant: markdown
description: ""
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
  row-gap: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-bottom: 2rem;
  width: 100%;
}
.entry-content.sharing-sessions .session-item .session-description,
.entry-content.sharing-sessions .session-item .session-link{
  background-color:#d84178;
  border-radius: 0.5rem;
  padding: 1rem;
}
.entry-content.sharing-sessions.malay-sessions .session-item .session-description,
.entry-content.sharing-sessions.malay-sessions .session-item .session-link{
  background-color: #a3c864;
}
.entry-content.sharing-sessions.tamil-sessions .session-item .session-description,
.entry-content.sharing-sessions.tamil-sessions .session-item .session-link,
.entry-content.sharing-sessions.preschools-exhibitors .session-item .session-description,
.entry-content.sharing-sessions.preschools-exhibitors .session-item .session-link{
  background-color: #9b4490;
}
.entry-content.sharing-sessions.english-sessions .session-item .session-description,
.entry-content.sharing-sessions.english-sessions .session-item .session-link{
  background-color: #fa0;
}
.entry-content.sharing-sessions.primary-secondary-exhibitors .session-item .session-description,
.entry-content.sharing-sessions.primary-secondary-exhibitors .session-item .session-link{
  background-color: #a3c864;
}
.entry-content.sharing-sessions .session-item p,
.entry-content.sharing-sessions .session-item a{
  color: #fff;
  font-size: 1.1rem;
  line-height: 1.2;
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
    align-items: flex-start;
    column-gap: 1rem;
    flex-direction: row;
  }
  .entry-content.sharing-sessions .session-item .session-description{
    flex: 5;
  }

  .entry-content.sharing-session-item .sharing-sessions-nav .inner-nav-wrapper .nav-btn{
    width: 45%;
  }
}
</style>
<div class="entry-content">

<p></p>
<h4>Thank You - Fully Booked</h4>
<p>
All our sharing sessions, interactive workshops, and entry tickets for exhibition hall are fully booked. Thank you for your strong interest and support!


</p></div>
<h4>Limited Walk-In Tickets on Actual Event Day</h4>
<p>
For those who did not manage to book the tickets to the exhibition, there will be walk-in tickets issued at regular intervals throughout the day. Kindly note that tickets are limited in quantity, admission is not guaranteed and subject to hall capacity.
	
Admission after 7pm does not require tickets, subject to hall capacity.
</p>