# Conference CfP App

This application should solve all the issues found with several CfP's with conferences. Most of the time people just want to submit their talks quickly and easily, so by providing a single tool that will deal with most of the burden should make the whole CfP process more enjoyable for both the speaker and conference organiser.

# Issues this tool wants to solve

## Speaker information

Most speakers already have a full profile on sites like [JoindIn](http://joind.in), so using the oAuth implementation of this site should immediately fetch the necessary information.

For speakers not yet registered with [JoindIn](http://joind.in), information can be gathered from [GitHub](https://github.com) which also provides oAuth.

## Talk submission

Each conference requires the same information, but often I see that things are missing or not covered. Maybe it's a good thing to have this project on [GitHub](https://github.com/DragonBe/conference-cfp-app) so it can be completed for all organisers to have the same approach and speakers know what information they need to provide.

A few common items that are returning on most CfP forms:

- Title
- Abstract
- Type of talk (lightning, regular talk or workshop)
- Duration of talk (20 minutes, 1 hour, 3 or 6 hours)
- Organiser information
- Speaker requirements (audio, flipboard, …)

## Management

Most of the times proposals are managed through a CSV, email or an online document. This is often a burden for the conference organisers who just want to view the proposals and decide on who they select for the conference. Another downside is when speakers update their profile or their talks, it's often not registered so a wrong abstract ends up in the schedule.

So, a general management dashboard should give you direct access to all the submitted information giving a direct view on the proposals, the speakers and their origins (important to figure out the costs).

# Licence

This tool is under [MIT license](LICENSE.txt).