# XSS in WonderCMS 3.4.3 (Settings -> Current page)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz.

**Description:** Cross-site scripting (XSS) vulnerability in Current Page of the Settings section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into several fields: 'Page Title', 'Page keywords' and/or 'Page description'.

## PoC
### Page Title
1. Enter to Current Page of the Settings section in the webpage and in 'Page Title' set the payload:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/07b89ca6-806d-46da-9b46-8db047ec1cc2)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/fb368df0-d56d-41f2-b10d-6b62b7d8fce1)
![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/4685f287-56b5-4ce1-86df-7da714fe1b53)
 


### Page keywords
1. Enter to Current Page of the Settings section in the webpage and in 'Page keywords' set the payload:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/67a20e0b-0f01-4233-99de-d8cfa86820aa)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/ea84c79a-a2cb-4118-b039-8f8b9883db4b)
![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/5c7219df-d602-44bc-9d0f-b1515f179c5a)
 


### Page description
1. Enter to Current Page of the Settings section in the webpage and in 'Page description' set the payload:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/10fc57bc-805c-423c-a8ef-bbc2fd03fc85)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/e83e3211-6a35-4958-9160-b8af27e666fc)
![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/6bdcd442-4946-4caf-b798-987123e60bca)
 

