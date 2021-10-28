static void UpdatePresence()
{
    DiscordRichPresence discordPresence;
    memset(&discordPresence, 0, sizeof(discordPresence));
    discordPresence.state = "z!roles";Roles are... Owner, Co-owner, Admin, Modator, Bots, Member, Verified
    discordPresence.details = "z!verify";Verify Type "ZS23" then do "z!verified"
    discordPresence.startTimestamp = "z!verified";You Have Succsesfully Verifed!
    discordPresence.endTimestamp = "z!createrole";What role name would you like to create?
    discordPresence.largeImageText = "z!create";Succsesfully Made Role!
    discordPresence.smallImageText = "z!info";Information Coding 9:46 Time Date : Thursday, October 2021 28 Made by ZesterPlayz - BMGO
    discordPresence.partyId = "ae488379-351d-4a4f-ad32-2b9b01c91657";
    discordPresence.partySize = 1;
    discordPresence.partyMax = 5;
    discordPresence.joinSecret = "MTI4NzM0OjFpMmhuZToxMjMxMjM= ";
    Discord_UpdatePresence(&discordPresence);
}
