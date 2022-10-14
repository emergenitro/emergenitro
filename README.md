# Hi, I am Karthik Sankar! :wave:


```CPP
#include <iostream>
#include <string>
using namespace std;

class info {
    public:
        string myName = "Karthik Sankar",
               myLocation = "Singapore",
               myWebsite = "workInProgress",
               followMeAt = "@itsthekarthik",
               mainCodingLanguages = "C++ and Python";
        int myGrade = 10, numOfCodingLanguagesIKnow = 13;
        void details();
};

void info::details(){
    cout << "Hello! I am " << myName << " and I live in " << myLocation;
}

int main(){
    info KarthikSankar;
    KarthikSankar.details();
    
    return 0; 
}
```

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=emergenitro)]
