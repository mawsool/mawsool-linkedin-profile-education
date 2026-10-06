# LinkedIn Education Scraper

**Get education from a LinkedIn profile URL: school, degree, field of study, years, and school URL. $1 per 1,000 profiles.**

Each school is one row. Use it for alumni checks and recruiting screens.

## What does a row look like?

```json
{
  "inputUrl": "https://www.linkedin.com/in/example",
  "fullName": "Example Person",
  "school": "Example University",
  "degree": "Bachelor of Science",
  "field": "Computer Science",
  "startYear": "2016",
  "endYear": "2020",
  "schoolUrl": "https://www.linkedin.com/school/example",
  "educationCount": 1,
  "success": true
}
```

## FAQ

### Can I search everyone who went to a school?

No. You start with profile URLs. This Actor reads the education on those profiles.

### Is one school one charge?

No. The profile is one charge. Several schools from that profile are included.

## Related Actors

Certifications and Patents, Work Experience, and Profile Details.

## Where to run it

Run the published Actor on Apify, or start from [mawsool.tech](https://mawsool.tech). This repository does not include the lookup address.
