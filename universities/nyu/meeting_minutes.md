# YACS @ NYU Meeting Minutes

## Meeting on 4/7/2018 @ 12PM EST

### Attendees:
- Richi Young
- Katie Burkhardt
- Bradley Brecher
- Hao Fuang
- Jody Simpson

### Organization of NYU team
- Bradley will organize the team and distribute tasks
- NYU team members will mostly communicate through Bradley
- We have the slack for direct communication

### Data / Registrar requirements
- NYU's registrar changes the system every year - opposite of RPI's problem
  - used to be private, is now public
- Seems unlikely they will be able to support an API integration
- That's OK, we can pull data from Albert
  - Will not be as elegant, but should work and still be interesting

### Work Plan
- NYU Integration:
  - Service to scrape data from Albert and transform it for YACS (!!)
    - Can be done in any language
    - Examples exist for Ruby (https://github.com/YACS-RCOS/adapter-banner-rpi)
  - Find & document key compatibility issues (!!)
    - Ways YACS stores or shows information that doesn't make sense for NYU
    - Tolerate lack of data NYU that cannot provide at this time
      - e.g., Albert does not show number of seats, only open or closed
    - Issues should be created for each thing that needs to be changed
- Plenty of issues available on the Core project not specific to NYU (see https://github.com/orgs/YACS-RCOS/projects/3)
- NYU students may not have frontend/framework/web experience but are excited to learn
  - Students should pick either frontend or backend due to the learning curve associated with both
  - Frontend uses Angular (4), backend uses Ruby / Ruby on Rails

### Development
- Every task should have an issue
- Students should comment on issues:
  - if they are unclear
  - to ask questions
  - to report progress
- "Can I use Windows to develop?"
  - If you are on Windows 10 yes, otherwise, probably not.
  - Often not worth the headache, we may not be able to help with issues

### Timeline
- "Can we actually get this done before registration?"
  - A month is a very short time. But...
  - If we get the Albert adapter working, and fix the key compatibility issues
  - We should aim for a beta test when registration starts
  - Should be a soft launch, as there will likely be issues
  - Most important thing is getting the Albert adapter in good shape. From there we can test and improve
  - Even if what we have is very unreliable / buggy come registration, doing a beta test would give us good feedback to go off of

### Code of Conduct
- Every student should look over the RCOS code of conduct used by the YACS project
