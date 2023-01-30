# JavaScript-CN
 ****************************************************** Understanding DOM  ***********************************************************

## Q-1
![image](https://user-images.githubusercontent.com/122484692/215387408-04f63e6c-2b56-48bb-9646-3387f8fb50ae.png)

## Q-2 
console.log(window.document==document);
<details><summary><b>Answer</b></summary>
 true
</details>

## Q-3 
console.log(window.location === document.location)
<details><summary><b>Answer</b></summary>
 true
</details>

## Q-3 
function test(){
return this;
}
console.log(test()==window);
<details><summary><b>Answer</b></summary>
 true
</details>

## Q-4
![image](https://user-images.githubusercontent.com/122484692/215388619-ad5679ee-aff1-43c7-8800-f74320aadfca.png)


## Q-5
![image](https://user-images.githubusercontent.com/122484692/215388792-94ac3f10-d306-44c0-abdc-1a4c0a70af51.png)

## Q-6
![image](https://user-images.githubusercontent.com/122484692/215388899-6320fc44-30e7-48b4-ae1e-da5f501504bf.png)

## Q-7
![image](https://user-images.githubusercontent.com/122484692/215389063-a87516c8-da0f-48a9-a7d3-649b05a623b7.png)

## Q-8
![image](https://user-images.githubusercontent.com/122484692/215389154-5f438aad-47ff-46a3-8f2f-c2b5bf656090.png)

## Q-9
![image](https://user-images.githubusercontent.com/122484692/215389218-dad0b872-2265-47d3-b92e-4c4e99af70fd.png)

## Q-10
![image](https://user-images.githubusercontent.com/122484692/215389264-4faa2338-d5df-4778-ac9d-6201cf41a51d.png)

## Q-11
![image](https://user-images.githubusercontent.com/122484692/215389367-0c49a58a-0528-4849-aea6-5c066e599f8b.png)

## Q-12
![image](https://user-images.githubusercontent.com/122484692/215389462-5f865f02-dc66-438f-a782-65692ae55f1b.png)

## Q-13
![image](https://user-images.githubusercontent.com/122484692/215389534-7bd3953d-78d7-4008-8f19-50c862fa5932.png)

## Q-14
![image](https://user-images.githubusercontent.com/122484692/215389580-c0af4657-8226-4405-879f-b71784b9036d.png)

## Q-15
![image](https://user-images.githubusercontent.com/122484692/215389623-a5b8bf28-1434-49cc-acb5-83f70995670c.png)

## Q-16
![image](https://user-images.githubusercontent.com/122484692/215389670-caae8035-79eb-413b-8abf-579a00700425.png)

## Q-17
![image](https://user-images.githubusercontent.com/122484692/215389719-c1dc5746-a17c-4234-85e6-b01bea663d29.png)

## Q-18
  <div id="parent">
    <button id="child">Child</button>
  </div>
  <script>
    var parent = document.querySelector('#parent');
      parent.addEventListener('click', function(){
        console.log("Parent clicked");
      });
    var child = document.querySelector('#child');
      child.addEventListener('click', function(){
        console.log("Child clicked");
      });
  </script>
<details><summary><b>Answer</b></summary>
child clicked parent clicked
</details>
