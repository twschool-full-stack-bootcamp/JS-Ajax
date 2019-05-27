# JS-Ajax

- 创建一个名为ajax的XHR对象，其示例用法如下：

```
  function myCallback(xhr){ 
    alert(xhr.responseText); 
  }
  ajax.request(“somefile.txt”,”get”,myCallback);
  ajax.request(“script.php”,”post”,myCallback,”first=John&last=Smith”);
```


