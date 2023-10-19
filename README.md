# Linkedin sales navigator scraper

Interested in using this scraper? Get it here: [Linkedin sales navigator scraper](https://apify.com/curious_coder/linkedin-sales-navigator-search-scraper)

Scrape linkedin profiles from sales navigator search results with email, company website and other important information

## How it works

Install [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension 

Login to your linkedin account

Click on the extension and export the linkedin cookies

Paste the cookies into this actor's `Linkedin cookie` input field

Search for leads on sales navigator and save the search using "Save search" button

Go to [Saved searches](https://www.linkedin.com/sales/search/saved-searches/people) page and click on last saved search 

Copy the link from address bar and paste it to actor `Search URL` input field

Enter start page and end page based on your requirements. You can access up to max 2500 results per search. 

If you enable `Deep search` option,  it will visit each profiles and scrape more information. 

Here is the sample output of this actor:

```json
{
	"profileId": "ACwAAAGHtboB_SK60RCbrgLUstRVuTcNlzAHfPU",
	"salesNavigatorUrl": "https://www.linkedin.com/sales/people/ACwAAAGHtboB_SK60RCbrgLUstRVuTcNlzAHfPU,NAME_SEARCH,3tl8",
	"companyName": "Xponential Fitness",
	"jobTitle": "Senior Vice President of International Development",
	"location": "Lake Worth, Florida, United States",
	"connectionType": 2,
	"firstName": "Daniel (Dan)",
	"lastName": "Adelstein",
	"openLink": false,
	"pendingInvitation": false,
	"premium": false,
	"saved": false,
	"viewed": true,
	"publicUrl": "https://www.linkedin.com/in/danadelstein",
	"profilePictureUrl": "https://media.licdn.com/dms/image/C4E03AQFelTC96_eCyQ/profile-displayphoto-shrink_100_100/0/1649968936543?e=1692835200&v=beta&t=TfjDsul8dX_OcuE-eGRDAK7Wnw2r7Og5IG73l_2JhLw",
	"profileBackgroundPictureUrl": "https://media.licdn.com/dms/image/C4E16AQGSyK_L6GSwng/profile-displaybackgroundimage-shrink_200_800/0/1648546335745?e=1692835200&v=beta&t=4IRITPZcjKIamXY5Pv5LX9RSwIDL2vpygYpMuQ6Yo7c",
	"lastInteractionType": "VIEW_PROFILE",
	"lastInteractionTime": 1687496301805,
	"publicId": "danadelstein",
	"currentPosition": {
		"endedOn": {},
		"startedOn": {
			"year": 2022,
			"month": 3
		},
		"companyName": "Xponential Fitness",
		"title": "Senior Vice President of International Development",
		"companyUrn": "urn:li:fs_salesCompany:19193147",
		"current": true,
		"location": "Irvine, CA. "
	},
	"educations": [
		{
			"endedOn": {
				"year": 1986
			},
			"startedOn": {
				"year": 1982
			},
			"schoolName": "University of Florida",
			"schoolUrl": "https://www.linkedin.com/school/uflorida/"
		}
	],
	"positions": [
		{
			"endedOn": {},
			"startedOn": {
				"year": 2022,
				"month": 3
			},
			"companyName": "Xponential Fitness",
			"title": "Senior Vice President of International Development",
			"companyUrn": "urn:li:fs_salesCompany:19193147",
			"current": true,
			"location": "Irvine, CA. "
		},
		{
			"endedOn": {
				"year": 2022,
				"month": 3
			},
			"startedOn": {
				"year": 2021,
				"month": 6
			},
			"companyName": "Mathnasium - The Math Learning Center",
			"title": "Associate Vice President of Franchise Development",
			"description": "Our mission is to help every child to understand and master math, because it will change their world. Starting in 2002 with one Mathnasium Learning Center in Los Angeles, we've grown to over 1,000 locations in communities around the world. Every day, we work to transform the lives of our students.",
			"companyUrn": "urn:li:fs_salesCompany:276439",
			"current": false,
			"location": "Los Angeles, California, United States"
		},
		{
			"endedOn": {
				"year": 2021,
				"month": 5
			},
			"startedOn": {
				"year": 2021,
				"month": 2
			},
			"companyName": "Orangetheory Fitness",
			"title": "Senior Vice President of International Development ",
			"companyUrn": "urn:li:fs_salesCompany:2773083",
			"current": false,
			"location": "Boca Raton, FL"
		},
		{
			"endedOn": {
				"year": 2021,
				"month": 2
			},
			"startedOn": {
				"year": 2017,
				"month": 9
			},
			"companyName": "Orangetheory Fitness",
			"title": "Vice President of International Developmnet ",
			"companyUrn": "urn:li:fs_salesCompany:2773083",
			"current": false,
			"location": "Boca Raton, Florida, United States"
		},
		{
			"endedOn": {
				"year": 2017,
				"month": 9
			},
			"startedOn": {
				"year": 2013,
				"month": 1
			},
			"companyName": "Orangetheory Fitness",
			"title": "Vice President of Franchise Development and Real Estate",
			"companyUrn": "urn:li:fs_salesCompany:2773083",
			"current": false,
			"location": "Boca Raton, FL"
		},
		{
			"endedOn": {
				"year": 2012,
				"month": 12
			},
			"startedOn": {
				"year": 2007,
				"month": 11
			},
			"companyName": "The Growing Room",
			"title": "Senior Vice President",
			"current": false
		},
		{
			"endedOn": {
				"year": 2007
			},
			"startedOn": {
				"year": 2006
			},
			"companyName": "Lawn Doctor, Inc.",
			"title": "Franchise Director",
			"current": false
		},
		{
			"endedOn": {
				"year": 2006
			},
			"startedOn": {
				"year": 2005
			},
			"companyName": "AllOver Media",
			"title": "Franchise Vice President",
			"current": false
		}
	],
	"primaryEmail": "danieladelstein@yahoo.com",
	"allEmails": [
		{
			"dataSource": "LINKEDIN",
			"emailAddress": "danieladelstein@yahoo.com"
		}
	],
	"numOfConnections": 7869,
	"unlocked": false,
	"summary": "Founded in 2017 and headquartered in Irvine, California, Xponential Fitness, Inc., is a curator of leading boutique fitness brands across multiple verticals. Through its mission to make boutique fitness accessible to everyone, the Company has built and curated a diversified platform of nine boutique fitness brands spanning across verticals including Pilates, indoor cycling, barre, functional training, stretching, rowing, dancing, boxing, running and yoga. In partnership with its franchisees, Xponential Fitness offers energetic, accessible, and personalized workout experiences led by highly-qualified instructors in studio locations across 48 U.S. states and 11 additional countries as of September 30, 2021.\n\n \n\nXponential Fitness' portfolio of brands includes Club Pilates, the nation's largest Pilates brand; CycleBar, the nation's largest indoor cycling brand; StretchLab, a concept offering one-on-one and group stretching services; Row House, a high-energy, low-impact indoor rowing workout; AKT, a dance-based cardio workout combining toning, interval and circuit training; YogaSix, the largest franchised yoga brand; Pure Barre, a total body workout that uses the ballet barre to perform small isometric movements; STRIDE, a treadmill-based cardio and strength training concept; Rumble, a boxing-inspired full-body workout; and BFT, a functional training and strength-based fitness program.",
	"skills": [
		{
			"name": "Franchising",
			"numOfEndorsement": 112
		},
		{
			"name": "Franchise Consulting",
			"numOfEndorsement": 13
		},
		{
			"name": "New Business Development",
			"numOfEndorsement": 26
		},
		{
			"name": "Sales",
			"numOfEndorsement": 76
		},
		{
			"name": "Small Business",
			"numOfEndorsement": 31
		},
		{
			"name": "Start-ups",
			"numOfEndorsement": 25
		},
		{
			"name": "Business Planning",
			"numOfEndorsement": 13
		},
		{
			"name": "Marketing Strategy",
			"numOfEndorsement": 31
		},
		{
			"name": "Sales Management",
			"numOfEndorsement": 18
		},
		{
			"name": "Strategic Planning",
			"numOfEndorsement": 24
		},
		{
			"name": "Business Development",
			"numOfEndorsement": 19
		},
		{
			"name": "Leadership",
			"numOfEndorsement": 24
		},
		{
			"name": "Retail",
			"numOfEndorsement": 12
		},
		{
			"name": "Entrepreneurship",
			"numOfEndorsement": 21
		},
		{
			"name": "Team Building",
			"numOfEndorsement": 71
		},
		{
			"name": "Lead Generation",
			"numOfEndorsement": 5
		},
		{
			"name": "Selling",
			"numOfEndorsement": 6
		},
		{
			"name": "Sales Process",
			"numOfEndorsement": 9
		},
		{
			"name": "Time Management",
			"numOfEndorsement": 1
		},
		{
			"name": "Gender Equality",
			"numOfEndorsement": 0
		},
		{
			"name": "Women's Issues",
			"numOfEndorsement": 0
		},
		{
			"name": "Workplace Relations",
			"numOfEndorsement": 0
		},
		{
			"name": "High Performer",
			"numOfEndorsement": 0
		},
		{
			"name": "Personal Development",
			"numOfEndorsement": 0
		},
		{
			"name": "Mental Health",
			"numOfEndorsement": 0
		},
		{
			"name": "Positive Psychology",
			"numOfEndorsement": 0
		},
		{
			"name": "Interpersonal Communication",
			"numOfEndorsement": 0
		},
		{
			"name": "Organization Skills",
			"numOfEndorsement": 0
		},
		{
			"name": "Self-care",
			"numOfEndorsement": 0
		},
		{
			"name": "Productivity Improvement",
			"numOfEndorsement": 0
		},
		{
			"name": "Self-confidence",
			"numOfEndorsement": 0
		},
		{
			"name": "Prioritize Workload",
			"numOfEndorsement": 0
		},
		{
			"name": "Performance Improvement",
			"numOfEndorsement": 0
		},
		{
			"name": "Stress Management",
			"numOfEndorsement": 0
		}
	],
	"headline": "Senior Vice President of International Development at Xponential Fitness (NYSE:XPOF)",
	"fullNamePronunciationAudio": {
		"urn": "urn:li:digitalmediaAsset:C4E04AQFtujGgIALwCw",
		"duration": 2136,
		"url": "https://dms.licdn.com/playlist/vid/C4E04AQFtujGgIALwCw/audio/0/1599250131319?e=1692835200&v=beta&t=GXeO4vVpy5jRwPcF9iMqFU5jKFxwRuGjAi3L_cSXTdM"
	}
}
```
