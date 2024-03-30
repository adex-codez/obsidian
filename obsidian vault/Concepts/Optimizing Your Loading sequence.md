
In every successful web page load, some critical components and resources become available at the right time to give you a smooth loading.
Loading sequence of a website affect core web vitals.
The reasoning why it is hard to have the most optimal website because there is gap between the developer expectation and the way browsers prioritizes resources on the page.

## Sub-optimal sequencing

Optimizing for the core web vitals requires not only the understanding of what each of the metrics means but also the order in which they occur and how they relate to different critical resources.

## Network/CPU Utilization

Downloading scripts sequentially allow the CPU to start processing the first one as soon as it is downloaded, rather than downloading all the scripts at once then we wait until each and every last script is downloaded which causes the page load to be slow.

## Third Party products.
Third party products are required to add common features and functionality to the website. This may include ads, analytics, social widgets, live chats and other emdeds that power the website.

## Platform quirks 
Browsers may differ in how they prioritize requests and implement hints.
Behavior particular to a specific browsers makes it hard to achieve the desired loading sequences consistently.

## Resource level optimization

Effective sequencing needs that the resources that are being sequenced to be served optimally so that they will load quickly.
Critical CSS should be inlined, Images should be sized properly, and JS should be code split and delivered incrementally.


## More on resource - relations, constraints and priorities

The following are resources that need to be considered before 



