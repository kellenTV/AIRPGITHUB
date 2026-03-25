This version is for if you want to make a website using this prompt and chartacter selection use github apis to load everything info .char .personas and .authors are all json you can look in the characters folder of the main branch for examples and we will also have examples here
# what you feed the ai should be in this format
{persona}  
username  
userdescription  
{personaend}  
{characterinfo start}  
character/groupname  
character/groupdescription  
starting senerio(can be blank)  
{characterinfo end}  
{historystart}  
all previous messages go here ex:  
{user}hello  
{character}{character="person"}hello to you  
{historyend}  
{current user message}  
what they said  
{current user message end}
