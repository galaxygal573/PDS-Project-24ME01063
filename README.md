N.S.Priyamahitha - 24ME01063
Like many of my peers, I was introduced to coding here in college. I was very interested in doing this project because creating a game seemed fun, although I didn't have much idea of what I wanted to make back then.
After a lot of contemplation, I settled on a simple dungeon crawler game that could be easily made and shown visually in text form as i'm not sure how to attach images yet. I was inspired by a lot of fantasy games, 
quite a lot by Undertale which is also a similar text-heavy game (with images too), and the Elder Scrolls and and many others. I wanted to give the player choices that would affect the storyline, and the method I opted 
for by giving passive routes was heavily inspired by Undertale.
I believe I was able to incorporate most of what I've learned throughout this semester into this project. I thoroughly enjoyed the whole process of writing down a storyline and designing simple maps and player routes.
The one I made here is pretty small, as the time crunch and I didn't wish to overcomplicate it too much. I wanted to emulate the 90s RPG Dungeon games as much as I could with my limited skills, one struggle included 
the repetition of an event in a certain tile/section which of course isn't realistic. I'm sure with more time and practice I can make an even more concise code with a complex storyline.
One issue I feel is the lack of context and control settings which I would like to explain here, The player is a Paladin who simply picks up a quest to rescue a young boy from a Dungeon. The Dungeon is a 5X5 section and you 
meet different enemies and situations throughout the whole area. You can fight some or exit passively, and you can even find some extra loot in some sections. I was unable to display it in the video but you can also lose 
in this game if you run out of HP.
I know there is room for a lot of improvement, but I feel that this project is a great starting place for me as I delve into this more in the future.
Thank you so much for reading.

28-10-24

I'm adding this side note to further detail about the code and how I've used different functions. The main loop follows the player viewing their map, moving to an adjacent tile, and encountering any event. This loop is to repeat until either the player succeeds in finding the boy or if the player faints from excessive damage. This three step loop was broken down into multiple easily accessible short functions. 
The first prints the dungeon to the user, the second displays to the user the choices for direction as not all tiles have the option to move in all 4 directions (Up, Down, Left, Right), the third takes the input and changes the Dungeon array to reflect the new position the next time it prints it and the fourth is a simple event checking function. If there is a major encounter in the selected tile then a nested function call is ensued. After the event, the system checks again to see if the player has either finished the game or has met their doom, if neither then the loop continues.
