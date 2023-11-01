# 153
## 153
### 153
#### 153
##### 153
###### 153

**153** *153* ***153*** ~~153~~

---

1.  First ordered list item
2.  Another item
    ..* Unordered sub-list.
3.  Actual numbers don't matter, just that's a number
    . . 1. Ordered sub-list
    ... 2.2nd
4.  And another number
    ...* note 1
    ...* note 2
    ***  note 3


![NKUST](nkust.png)

---

- [ ] To do list
- [x] To do list

---

```python
s = "python highlighting text"
print(s)
```

```js
var s = "javascript syntax text" ;
alert(s) ;
```
---

| Tables | Are | Cool |
|:-------|:---:|-----:|
|col 3 is|right-aligned|$1600|
|col 2 is|centered|$12|
|zebra stripes|are neat|$1|

|Markdown|Less|Pretty|
|:-------|:---|:-----|
|*Still*|`renders`|**nicely**|
|1|2|3|



---
## zuvio
請新增一個CShape的子類別CTriangle，其constructor 共有三個double的參數 a,b,c (為直角三角形的三個邊長)，其面積為0.5*a*b，
請寫出CTriangle的類別程式與產生其物件的main 程式(顏色為紅色，a=3, b=4, c=5) 程式碼請放在個人的github 答案請列出其連結

CShape.java        
abstract class CShape{
    protected String color;
    public void setColor(String str){
        color = str;
    }


    public abstract void show();
}

           
CTriangle.java
class CTriangle extends CShape{
    double ca, cb, cc;
    public CTriangle(double a, double b, double c){
        ca=a;
        cb=b;
        cc=c;
    }
   
    public void show() {
       
        System.out.print("color="+color+"  ");
        System.out.print("area="+0.5*ca*cb);
    }
   
}

請寫出相對應的java code (github 連結)
import java.util.ArrayList;
import java.util.List;

public class Student {
    private String name;
    private List<Course> courses;

    public Student(String name) {
        this.name = name;
        this.courses = new ArrayList<>();
    }

    public boolean addCourse(Course course) {
        if (courses.size() < 10) {
            courses.add(course);
            return true;
        }
        return false;
    }

    public boolean removeCourse(Course course) {
        return courses.remove(course);
    }

    public List<Course> getCourses() {
        return courses;
    }

    // Other getters, setters, and relevant methods
}

public class Course {
    private String courseName;

    public Course(String courseName) {
        this.courseName = courseName;
    }

    // Getters, setters, and other relevant methods
}
