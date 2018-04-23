# April 22

## Side Projects

#### VegemiteSoup.com
- [x] Fix & clean up broken post styles in Jekyll blog
  - For future: need to re-organize & strip out unused CSS

#### ELK - Elasticsearch, Logstash, & Kibana
- [x] Add Page Previews piece of Elasticsearch demo application
**Next steps:**
  - Customize application, use a different data source
    **Ideas:**
      - Hook up to generic log output, for example, the docker containers we run at work, and add visualizations about those logs
      - Users can upload correspondences they've had with someone else and the application will analyze how that person types. Maybe then it could take an input a paragraph and have it converted to look like it was written by the other person, or at least give hints on how they could make it more similar to the other person's style.
  - Add MongoDB to application
  - Add logic to sync Elasticsearch and MongoDB
  - Add users, login, authorization etc.