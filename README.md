- 👋 Hi, I’m @OtakuOnMars
- 👀 I’m working on intview process. But for a old head in the industry and not native at US SW engineer, I need to spend time and warning up.
- 🌱 I will use C for the first stage to leetcoding....

-2024/05/21 Days 1
Learning to use add key and create key to sync and update code to github.

Local mechaine - 
create a new ssh key - 
"ssh-keygen -t ed25519 -C "xxxxx@xxxxx""
To create a ed25519 key pair and save to project_using_key
move the key pair to ~/.ssh/
"mv "the_gen_key" ~/.ssh/"
add the key to ssh_agent
"ssh-add ~/.ssh/"the_gen_key""

ok. Now your local key is set

Github server -
Click the project and select "Setting"
Search the left bar "Deploy Keys" and click
Adding "Add deploy key"
For Title "" -> please add the name you want
For key "" -> please dump your the_gen_key.pub key by
"cat ~/.ssh/xxxxx.pub" and it should be looked like below
==> ssh-ed25519 xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxw4 xxxxxx@xxxxx.xxx
Copy the key to the Key column.
Then you could see the key added on web.

Then you could clone and push key to the github server.

<!---
OtakuOnMars/OtakuOnMars is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
