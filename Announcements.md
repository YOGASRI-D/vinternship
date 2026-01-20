---
layout: page
title: Announcements
permalink: /announcements/
order: 1
announcements:
    - title: "LinkedIn Post - First Week Internship Experience"
      date: "18th Jan 2026"
      description: "Share your first week internship experience on LinkedIn to build your professional network and engage with the cohort."
      content: "We want to incentivize your LinkedIn activity by throwing a challenge with exciting gifts and perks in store. Create a post sharing all that you have learnt during your first week's internship experience. This will help you build connections with the current cohort, expand your network as people comment on your posts, and potentially discover new opportunities. Write a short and crisp message, include a GenAI image to attract attention, tag the supporting organizations (Vicharanashala lab, Annam.ai, IIT Ropar, NPTEL, and your college), and tag the mentors. Share your post link on the Cliq channel. For complete guidelines and detailed instructions, visit the [LinkedIn Post Activity](../linkedin_post/) page."
    - title: "ViBe Learning Activity & HP Opportunity"
      date: "20th Jan 2026"
      description: "Pinterns are encouraged to log in to ViBe at 9:00 PM today and engage with course content for at least 30 minutes to earn Health Points."
      content: "Today at 9:00 PM, all Pinterns are encouraged to log in to ViBe and actively engage with the course content on ViBe for at least 30 minutes as part of their regular learning activity. This is a great opportunity to get ahead in your course progress, explore the platform, and earn positive Health Points (HP) for participation. Participants who log in and remain actively engaged during this time will be rewarded with additional HP. We strongly encourage everyone to take part and make the most of this learning window. Your participation and consistency matter. Let’s learn, explore, and progress together 🚀"

    # - title: ""
    #   date: ""
    #   description: ""
    #   content: ""
#   - title: "The Self-Healing Endorsement Network"
#     date: "January 15, 2026"
#     description: "Understanding the endorsement network system, audit process, incentives, and dashboard challenge for visualizing endorsement chains and network health."
#     content: |
#       **Step 1: Understand the network**
      
#       The Endorsement Network functions on a simple rule: students can endorse each other. Crucially, every line of endorsements must ultimately link back to a Jedi holder, who possesses the Gold, Silver, and Bronze tiers. The more students connected to a Jedi holder, the higher their reputation. Any groups that fail to connect to a Jedi holder form "floating islands" and are deemed inactive within the system.
      
#       **Step 2: Follow endorsement rules**
      
#       Students are restricted to receiving only one endorsement, yet they have the freedom to provide multiple endorsements to others. Crucially, any endorsement can only be made after the associated task or case study has been successfully finished.
      
#       **Step 3: Know how audits work**
      
#       Bhavna conducts audits to detect defaulters. If a defaulter is found, the entire endorsement path connected to that person is checked. A 50% penalty is applied to everyone in that connected group. The defaulter and anyone who fails the audit are removed from the network. Anyone Bhavna certifies as "good" can be recruited by anyone. Gold ticket holders can assist Bhavna during audits.
      
#       **Step 4: Understand incentives**
      
#       Whenever a new person joins a connected group, everyone in that group receives a 5% health point increase. This increase is calculated as 5% of their current health points plus 5% of the new member's health points.
      
#       **Step 5: Work with the data**
      
#       Students will be given a simple three-column dataset: Member 1, Member 2, and Action.
      
#       The action can be added (Member 1 endorsed Member 2), deleted (Member 1 de-endorsed Member 2), or default (Member 1 is a defaulter and Member 2 is the parent).
      
#       **Step 6: Your challenge**
      
#       Using this data, students must create a dashboard that visualizes endorsement chains, penalties, incentives, and overall network health. The design and style are completely open-ended.

#       ***Form for Endorsement's* [Endorse here](https://forms.gle/BfSfhWbxaMnqbWBa6){:target="_blank"}**
---

[← Back]({{ site.baseurl }}/)

## 📢 Latest Announcements

{% if page.announcements.size > 0 %}
{% for announcement in page.announcements %}

---

### {{ announcement.title }}

**📅 {{ announcement.date }}**

{% if announcement.content %}
{{ announcement.content }}
{% else %}
{{ announcement.description }}
{% endif %}

{% endfor %}
{% else %}
<div style="text-align: center; padding: 40px; color: #666;">
  <p style="font-size: 1.2em;">📭 No announcements at the moment</p>
  <p>Check back later for updates!</p>
</div>
{% endif %}

---

[← Back]({{ site.baseurl }}/)
