# LovooUserActivity
Lovoo User Activity from 2015

(Courtesy: Utkarsh Singh of Kaggle)

SUMMARY

When Dating apps like Tinder were becoming viral, people wanted to have the best profile in order to get more matches and more potential encounters.
Unlike other previous dating platforms, those new ones emphasized on the mutuality of attraction before allowing any two people to get in touch and chat. This made it all the more important to create the best profile in order to get the best first impression.

Parallel to that, we Humans have always been in awe before charismatic and inspiring people. The more charismatic people tend to be followed and listened to by more people.
Through their metrics such as the number of friends/followers, social networks give some ways of "measuring" the potential charisma of some people.

In regard to all that, one can then think:

what makes a great user profile ?
how to make the best first impression in order to get more matches (and ultimately find love, or new friendships) ?
what makes a person charismatic ?
how do charismatic people present themselves ?
In order to try and understand those different social questions, I decided to create a dataset of user profile informations using the social network Lovoo when it came out. By using different methodologies, I was able to gather user profile data, as well as some usually unavailable metrics (such as the number of profile visits).

CONTENT

The dataset contains user profile infos of users of the website Lovoo.

The dataset was gathered during spring 2015 (april, may). At that time, Lovoo was expanding in european countries (among others), while Tinder was trending both in America and in Europe.
At that time the iOS version of the Lovoo app was in version 3.

Accessory image data
The dataset references pictures (field pictureId) of user profiles. These pictures are also available for a fraction of users but have not been uploaded and should be asked separately.

The idea when gathering the profile pictures was to determine whether some correlations could be identified between a profile picture and the reputation or success of a given profile. Since first impression matters, a sound hypothesis to make is that the profile picture might have a great influence on the number of profile visits, matches and so on. Do not forget that only a fraction of a user's profile is seen when browsing through a list of users.

https://s1.dmcdn.net/v/BnWkG1M7WuJDq2PKP/x480

Details about collection methodology
In order to gather the data, I developed a set of tools that would save the data while browsing through profiles and doing searches. Because of this approach (and the constraints that forced me to develop this approach) I could only gather user profiles that were recommended by Lovoo's algorithm for 2 profiles I created for this purpose occasion (male, open to friends & chats & dates). That is why there are only female users in the dataset.
Another work could be done to fetch similar data for both genders or other age ranges.

Regarding the number of user profiles
It turned out that the recommendation algorithm always seemed to output the same set of user profiles. This meant Lovoo's algorithm was probably heavily relying on settings like location (to recommend more people nearby than people in different places or countries) and maybe cookies. This diminished the number of different user profiles that would be presented and included in the dataset.

Inspiration
As mentioned in the introduction, there are a lot of questions we can answer using a dataset such as this one. Some questions are related to

popularity, charisma
census and demographic studies.
Statistics about the interest of people joining dating apps (making friends, finding someone to date, finding true love, …).
Detecting influencers / potential influencers and studying them
Previously mentioned:

what makes a great user profile ?
how to make the best first impression in order to get more matches (and ultimately find love, or new friendships) ?
what makes a person charismatic ?
how do charismatic people present themselves ?
