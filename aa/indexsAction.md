indexsAction
===============






* Class name: indexsAction
* Namespace: 
* Parent class: ApiController



Constants
----------


### ABC_AAA

    const ABC_AAA = '555'





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    protected string $name





* Visibility: **protected**


### $sex

    protected mixed $sex





* Visibility: **protected**


### $description

    protected string $description





* Visibility: **protected**


Methods
-------


### getUsers

    array indexsAction::getUsers(string $testParam, string $height)

根据查询参数获取用户的信息



* Visibility: **public**


#### Arguments
* $testParam **string** - &lt;p&gt;测试使用的参数, 只有这个参数会在文档里面显示出来&lt;/p&gt;
* $height **string** - &lt;p&gt;身高&lt;/p&gt;



### getIndex

    array indexsAction::getIndex()

根据查询参数获取用户的信息

```
  get 请求:
  [
     param string age 用户的年纪
     param string nickname 用户的昵称
   ]
```

* Visibility: **public**




### getString

     indexsAction::getString()





* Visibility: **public**




### setInteger

     indexsAction::setInteger()





* Visibility: **public**



