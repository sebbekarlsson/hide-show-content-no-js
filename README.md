# hide and show content without javascript

> screenshot:

![nojs.png](nojs.png)


> code:

    <div class='details-wrap'>
        <details>
            <summary>change name</summary>
            <input class='input-text' type='text' value='John Doe'/>
            <button class='btn'>save</button>
        </details>
        <details open>
            <summary>change content</summary>
            <textarea>lorem ipsum dolum ipa</textarea>
            <button class='btn'>save</button>
        </details>
        <details>
            <summary>change image</summary>
            <input type='file'/>
            <button class='btn'>save</button>
        </details>
    </div>    
