A small babel plugin package designed to make transitioning from jstl to jsx simpler.  

```javascript
<ForEach var='thisItem' items={items} index='index'>
    {thisItem}
</ForEach>

<If test={condition}>
    contents
</If>

<Choose>
    <When test={condition}>
        if
    </When>
    <Otherwise>
        else
    </Otherwise>
</Choose>
```

Pretty much a clone of jsx-control-statements but more customized for my experiences.  