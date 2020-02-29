
### README: Data

1. Full data can be downloaded from [Amazon Review Data (2018)](https://nijianmo.github.io/amazon/index.html)
   * Book review 5-core contains 27,164,983 reviews
2. Data in this folder
   * Books_5_5000.json - 5000 Book reviews in JSON format
   * Books_5_20000.json.gz - 20,000 Book reviews zipped in gz
3. Data attributes
   * overall - rating of the product
   * verified - verified purchase
   * reviewTime - time of the review (raw)
   * reviewerID - ID of the reviewer
   * asin - ID of the product
   * reviewerName - name of the reviewer
   * reviewText - text of the review
   * summary - summary of the review
   * unixReviewTime - time of the review (unix time)
4. Sample data
```
{
  "overall": 5,
  "verified": true,
  "reviewTime": "06 20, 2016",
  "reviewerID": "AVP0HXC9FG790",
  "asin": "0001713353",
  "reviewerName": "Amazon Customer",
  "reviewText": "The kids loved it!",
  "summary": "Five Stars",
  "unixReviewTime": 1466380800
}
```
