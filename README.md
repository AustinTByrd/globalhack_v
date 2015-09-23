# GlobalHack V

Source code repository for Justek code

Auto github push script:
```
$  while [ true ]; do echo "Grabbing..."; rsync -avz pashleco@pashle.com:public_html . && git add . && git commit -m "Autocommit - $(date +%y%m%d-%H%M)" && git push origin HEAD; echo "Sleeping..."; sleep 60; done

```
## PASHLE - Public Access System for Helping Law Enforcement
#### Home Screen
###### By searching with their last name and the last four digits of their social security number, an individual is able to access important data that was previously unavailable.
![screen shot 2015-09-22 at 2 12 57 pm](https://cloud.githubusercontent.com/assets/14076100/10034027/eac64c6c-6152-11e5-8dd8-6c14b1ad0245.png)
#### After Verifying Personal Information
##### Citations
###### Options for viewing tabs of personal municipal court data. Here, an individual's citations can be viewed.
![screen shot 2015-09-22 at 2 13 25 pm](https://cloud.githubusercontent.com/assets/14076100/10034043/1319b3de-6153-11e5-89f0-74b9f68c56f0.png)
##### Violations
###### An individual can view their current and historical violations. Each violation has a button that displays a lightbox containing specific information. On the right of each row are How To Resolve and Pay Now buttons. How To Resolve leads to a FAQ page, and the Pay Now button leads to a page with various payment options.
![screen shot 2015-09-22 at 2 13 28 pm](https://cloud.githubusercontent.com/assets/14076100/10034045/16d26750-6153-11e5-9760-f5da2705f8bf.png)
##### Warrants
###### Outstanding and past warrants issued are displayed here with similar options.
![screen shot 2015-09-22 at 2 13 30 pm](https://cloud.githubusercontent.com/assets/14076100/10034048/1ab33bec-6153-11e5-95df-09c52cb0abd1.png)
#### Payment
###### Paypal's API is implemented to allow individuals to pay with a debit card, as well as other options such as paying with a money order and paying over the phone. There is also an option for those who are eligible to pay by volunteering.
![screen shot 2015-09-22 at 2 15 34 pm](https://cloud.githubusercontent.com/assets/14076100/10034052/27be34ae-6153-11e5-925f-ae70cf4dfc25.png)
#### Volunteering
###### Volunteering eligibility is verified before moving on. Organization's are able to submit information and to be posted, where individuals can choose how they would like to work off their citations, violations, or warrants.
![screen shot 2015-09-22 at 2 16 02 pm](https://cloud.githubusercontent.com/assets/14076100/10034057/2f06a7b4-6153-11e5-99e3-65254d9aa824.png)
#### Responsive Design
###### We used a bootstrap since we only needed a quick prototype and because we wanted individuals who only have a smartphone to access the site. Those without a smartphone are able to access the same data through the texting service Twilio.
![screen shot 2015-09-22 at 7 25 20 pm](https://cloud.githubusercontent.com/assets/14076100/10035457/042a43f4-6160-11e5-9a8b-1585d64a31f6.png)

