# Aleksey Khamiakov
#### PHP Developer

**********************************************

#### Personal Information
* **Email:** alekseyrs65@gmail.com 
* **Skype:** scarabey01
* **Vk:** vk.com/tocker

**********************************************

#### About Myself
I have strong technical skills as well as excellent interpersonal skills, enabling me to interact with a wide range of clients. I am eager to be further improve my IT skills.  My greatest passion is in life is using my technical know-how to benefit other people and organisations.

**********************************************

#### My skills
* *PHP* 
* *HTML & CSS*
* *JS*
* *SQL/MySQL*
* *MVC frameworoks: Magento, Prestashop, Drupal*
* *Git*

**********************************************

#### Sample code
```
new Ajax.Request(url, {
                method: 'get',
                    onComplete: function(transport){
                        if(transport.status==200){
                            if(transport.responseText!=0){
                                var MESSAGE = ''; var i=1;
                                var ERROR = transport.responseText.unescapeHTML().evalJSON();
                                $H(ERROR).each(function(error){
                                    MESSAGE += i +". "+error.value + "<br />";
                                    i++;
                                });
                                fAlert("", __(MESSAGE));     
                                if(this.HANDLER_ERROR.size()>0){
                                    for(var i=0;i<this.HANDLER_ERROR.size();i++){
                                        if(Object.isFunction(this.HANDLER_ERROR[i]))
                                            this.HANDLER_ERROR[i]();
                                    }
                                }
                            }
                        }
                    }.bind(this)
            });

```

**********************************************

#### Education
I graduated from the Minsk College of Entrepreneurship. And I graduated BSUIR with a degree in software engineer.

**********************************************

#### CERTIFICATES
Zend Certified Engineer (08/2021)

**********************************************

##### WORK EXPERIENCE
- PHP Developer (Prestashop)
    - Developed and maintained PHP applications using Prestashop framework.
    - Designed and implemented custom modules and functionalities to meet client requirements.
    - Collaborated with cross-functional teams to ensure seamless integration of backend systems.
    - Conducted code reviews and debugging to optimize performance and ensure code quality.
    - Worked on database design, query optimization, and data migration tasks.
    - Implemented best practices for security and data protection.
    - Collaborated with clients to understand their needs and provide technical solutions.
    - Stayed updated with the latest industry trends and emerging technologies
- PHP Developer (Drupal) 
    - Developed and maintained PHP applications using Drupal CMS.
    - Customized and extended Drupal modules and themes to meet client requirements.
    - Collaborated with a team of developers to implement complex features and functionalities.
    - Conducted code reviews and performed debugging to ensure code quality and optimize performance.
    - Implemented security measures and followed best practices for secure coding in Drupal.
    - Collaborated with clients to understand their needs and provide technical solutions.

**********************************************

##### LANGUAGES
- Belarusian/Russian *Native*
- English *Intermediate*