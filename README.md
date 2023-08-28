## World Clock for Remote Teams
<img src="https://github.com/dano707/world-clock/assets/23415008/e3eb1e90-7d58-4f23-9edc-92e854fc1c8b" width="300px">

This is a proof of concept for a tool that allows teams to keep track of coworkers' local time in relation to their own. It also includes information about the user's weather and location. This was a peronal project to explore APIs and time zone conversions, while I continued expanding my understanding of React. 

I use the [World Time API](https://worldtimeapi.org/) to get timezone data and the [Weather API](https://www.weatherapi.com/) to get weather info based on a user provided zipcode. 

### Directions
1. Visit the page at [https://dano707.github.io/world-clock/](https://dano707.github.io/world-clock/). 
2. Click the dropdown and select a user, or type in your name. 
3. Enter your zipcode and click `Lookup` to get your weather. You can also enter any valid US zipcode if you don't want to enter your own. (e.g. NYC is 10001)
4. Confirm the informaiton on the screen is correct, including `Location`, `Local Time`, and `Timezone`. If everything looks ok, press `Looks Good`
5. You should now see a screen that looks similar to this. You can sort the list by clicking on `Name`, `Role`, or `Timezone` headers. 

<img src="https://github.com/dano707/world-clock/assets/23415008/0b7e4178-76ed-4399-a4df-c2c9f9774dbb" width="400px">

Information is saved in your browser's local storage, so if you leave the page and come back, you won't need to re-enter your information (unless you clear your browser's cache, or your browser settings don't allow local storage).

You can always reset the page by clicking the `Reset` button in the top left corner.

### Takeaways 
I learned very quickly that working with time is complex and has a ton of nuance to account for. I didn't want to overcomplicate things so I displayed user data in the US, but this could be expanded to support any location with a few modifications. 

I also found that I still have a lot to learn about how to structure React components, and how to pass data between them. 

There are a ton of improvements that I could make here, but I'm still very happy with the result. I don't expect to make any future changes, however I might consider rebuilding it from scratch to achieve a better structure and more efficient code.

However, if you have any suggestions or feedback, please feel free to reach out by commenting on the code!

Thanks for having a look! 

---


_Names and images are generated randomly (except for one)._
