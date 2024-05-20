# XSS in WonderCMS 3.4.3 (SETTINGS -> CURRENT PAGE)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz Pérez.

**Description:** Cross-site scripting (XSS) vulnerability in CURRENT PAGE of the SETTINGS section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into several fields: 'PAGE TITLE', 'PAGE KEYWORDS' and/or 'PAGE DESCRIPTION'.

**CVE:** CVE-2024-32338, CVE-2024-32744 y CVE-2024-32745.

## PoC
### PAGE TITLE (CVE-2024-32338)
1. Enter to Current Page of the SETTINGS section in the webpage and in 'PAGE TITLE' set the payload:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/d2e20e01-b7a2-401c-b1ad-9932292ea020)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/02fafa77-0ce3-4891-9cdd-9eeae869ac85)
![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/d3b6da8e-5e3f-4c10-91f8-7f22986a4b1d)



### PAGE KEYWORDS (CVE-2024-32744)
1. Enter to Current Page of the SETTINGS section in the webpage and in 'PAGE KEYWORDS' set the payload:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/fbb9ad74-e719-4789-a5e4-7e7763350868)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/6d3ef3b4-d716-4f48-928d-6076956e0cb6)
![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/9438a992-4ec0-420b-aa5a-966d0c9b7abc)
 


### PAGE DESCRIPTION (CVE-2024-32745)
1. Enter to Current Page of the SETTINGS section in the webpage and in 'PAGE DESCRIPTION' set the payload:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/ee578959-b408-4d66-bfe2-c40a2f680142)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/9765ff15-d21c-4e40-8f59-45ba24d11f65)
![image](https://github.com/adiapera/xss_current_page_wondercms_3.4.3/assets/165512291/90d05415-2bf1-4c89-a4e1-595ea2ca6313)

 

