# include<iostream>

using namespace std;

namespace ProjectResume;
{
    class Resume;
    {
        string name;
        string title;
        string phone;
        string email;
        string summary;
        Experience experiences;
        Project projects;
        Education educations;
        string language[20];
        string skills[50];

        public:
        // getter
        string getname(void);
        {
            return name;

        };
        string gettitle(void);
        {
            return title;

        };
        string getphone(void);
        {
            return phone;

        };
        string getemail(void);
        {
            return email;

        };
        string getsummary(void);
        {
            return summary;

        };
        Experience getexperiences(void0);
        {
            return experiences;

        };
        Project getprojects(void);
        {
            return projects;

        };
        Education geteducations(void);
        {
            return educaaaations;

        };
        string getlanguage(void);
        {
            return language[20];

        };
        string getskills(void);;
        {
            return skills[50];

        };
        // setter

        void setname(string name);
        {
            this->name = name;

        }
        void settitle(string title);
        {
            this->title = title;

        }
        void setphone(string phone);
        {
            this->phone = phone;

        }
        void setemail(string email);
        {
            thi->email = email;

        }
        void setsummary(string summary);
        {
            this->summary = summary;

        }
        void setexperiences(Experience experiences);
         {
            this->experiences = experiences;

         }
         void setprojects(Project projects);
         {
            this->projects = projects;

         }
         void seteducations(Education educations);
         {
            this->eucations = educations;

         }
         void setlanguage(string language)[20];
        {
            this->language[20] = language[20];

        }
        void setskills(string skills[50]);
        {
            this->skills[50] = skills[50];

        }
        // constructor
        Resume(string name, string title, string phone, string email, string summary, Experience experinces, Project projects, Education educatoion)
        {
            this->name = name;
            this->title = title;
            this->phone = phone;
            this->email = email;
            this->summary = summary;
            this->experiences = experiences;
            this->projects =projects;
            this->educations = educations;
            this->language[20] = language[20];
            this->skills[50] = skills[50];

        };

    


        

    }
}
