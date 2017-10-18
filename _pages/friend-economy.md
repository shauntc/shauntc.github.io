---
layout: page
title: Friend Economy
permalink: "/projects/friend-economy/"
---  
# FriendEconomy <a href="https://github.com/shauntc/FriendEconomy"><span class="icon-github socials"></span></a>
---
*Tech: Swift, Firebase Database, Dispatch Queues*
<div style="position: relative;
			padding-bottom: 56.25%;
			padding-top: 25px;
			height: 0;">
	<iframe style="position: absolute;
					top: 0;
					left: 0;
					width: 100%;
					height: 100%;" src="https://www.youtube.com/embed/bWRS_DnWzSU" frameborder="0" allowfullscreen></iframe>
</div>
Final Project for Lighthouse Labs (2 Week build time)

FriendEconomy was built for friends to share bills for two reasons:
  - It takes forever to pay with a bunch of friends when everyone has cards
  - It is equally psychologically "painful" to pay for a large bill as it is a small
  
Put a bill into FriendEconomy and it notifies whoevers turn it is to pay the bill and handles everything else in the background. Its designed to be quick and require minimal interaction. It is designed to eliminate the complexities of splitting bills between friends so that they can spend more time enjoying eachothers company. 

FriendEconomy uses Firebase realtime database in order to reduce lag time between clients; it is designed for near instant response between clients.

FriendEconomy uses seperate dispatch queues for each object manager to quickly react to new data sent by Firebase and prevent downloads from affecting the user experience. These queues send notifications back to the view controller when new data is available to update the user interface. 

