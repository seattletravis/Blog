# Travis Lamberte - Dev Log is a Blog

## Date: 1/28/2024

## Title: Another day another job application

Hello Everyone!

It's another day and another job application. I see a lot of people like to document all the job applications they submit and if there was a response, a ghosting, or a interview. It's so much work just doing all the applying that I never felt like I had enough steam to go through that extra step. Some times I wish I had that data so I could fixate over it... On the other hand maybe its best that I don't have the data.

Because of the underwhelming response of employers who seem interested in giving me a job, I think it's reasonable to think of a way to start my own software business. They call this a 'start up' but I'm just going to not call it that, because whenever you say 'start up' to tech guys they start to think that it's only something that only seasoned developers do, but lets face it Elon, Jeff, Bill, and Mark they we're super green when they started, and they really didn't know how to code all that well either, sure they figured it out as the went but they didn't let not beng good at coding stop them from trying. So here we are...

I did finish the Node class last week and I think it would be a good idea to fortify that knowledge before I move on other languages, so I decided to build an API that allows the user to select a territory on a map as their service territory, they when a client send their address, the API will return true if the client is in the user's service territory. Taking this one step further I think that given multiple users, the API will return a list of users that service the clients address.

I'm just now looking at building this API which is doiable, but i'd like to do it in a what in which it it's scalable. Lets talk this through.

### _Method 1 Store Territory Selected Address in Object_

The user will selected all the address' that they are willing to service. There can even be multiple service tiers, $ for tier 1, $$ for tier 2, and $$$ for tier 3. The user can select address by using a map feature where they highlight an area on a google map. google may already have a selection feature like this availalbe. Once the user selects all the addresses then that data goes into a object. Then when the client sends the service address the userObject.territoryTier1.addresses list is check to see if the client.serviceAddress is present. If it is then return true and push the user to the list of users who service the clients address.

### _Method 2 get 'As Bird Flies' distance between both addresses_

User specifies territory center and territory radius, lets say they specify their home base address, and 5 miles. The API will take the user address and client address and calculate the distance between them. If it's < 5 miles it returns true.

### _Method 3 get 'travel distance from map API' between both addresses_

Like method 2 but instead of calculating the distance as a bird flies, we'll use a maps api to get the 'travel distance' based on road info, this may also include 'average travel time' that can be used by the user to determine territory settings.

Well I think I have enough here to start building out my API. It'll be challenging but I think I can produce something that works.

This is Travis, signing off.
