# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

I have chosen to deploy and App Service solution. My main reasoning behind this is:
* The cost is lower
* The implementation is more straightforward
* My app is very simple (minimal compute requirements) and I am the only consumer

### Assess app changes that would change your decision.

I may in future change my mind about this and implement a VM solution if, for instance:
* I decided to extend the application features in a complex manner that for some reason required niche OS configuration
* I decided to open my app to the whole world and for some reason it became hugely popular and I wanted to implement load balancing
