## Develop

1. Clone the repo
2. Switch to **develop** branch
3. Make a work branch like *my-new-feature-branch* and switch to that
2. Make sure docker is running
3. Inside the root do `docker-compose up` It pulls the image and starts hugo server 
4. Open http://localhost:1313 on you browser and see the site
5. Continue work the site at http://localhost:1313 will get automatically updated
6. Once the work is done commit to repo and check in the work branch.
7. Create a pull request against **develop** and request for a review
8. Once reviewer approves and merges to develop then go to next step

## Merge to Master
1. Create a PR for merging develop to master
2. Reviewer approves it then merge to master

## Build Master
1. Pull latest changes to from master to your local master branch
2. Build with this command `docker-compose run --rm app hugo`

## Deploy the site
1. Commit and push master to origin (github)

### Make sure the site looks good with changes