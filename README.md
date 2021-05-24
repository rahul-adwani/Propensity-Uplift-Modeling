# Propensity-Uplift-Modeling

### In this exercise, we are going to evaluate CausalLift package for building an Uplift Model to help a Digital Marketer on the below two fronts:
- Increase Revenue by Improving Conversion Rates
- Reduce Costs by Reducing Cost Per Click

![Image - Uplift Model](https://raw.github.com/rahul-adwani/Propensity-Uplift-Modeling/main/images/uplift.jpg)

# What do we need to do?

### We need to identify the customers who are Persuadables and approach them with Digital Marketing Campaigns
- This will help us in running campaign operations in a much more efficient way with a very high conversion rate
### We need to avoid all the other 3 types of customers - Sure Things, Do Not Disturb and Lost Causes
- This will help us save unnecessary costs and hence improving the Cost Per Click

### One Model Process

<!DOCTYPE html>
<html lang="en">
   <head>
	 <script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.0.0/mermaid.min.js"></script>
    </head>
	 
<body>
 <pre><code class="language-mermaid">graph LR
A--&gt;B
</code></pre>

<div class="mermaid">graph LR
A[Dataset with Treatment = 0 ] ----> B((Model Classifier))
C[Dataset with Treatment = 1 ] ----> B((Model Classifier))
B --> E{Uplift}
</div>
	
</body>
<script>
var config = {
    startOnLoad:true,
    theme: 'forest',
    flowchart:{
            useMaxWidth:false,
            htmlLabels:true
        }
};
mermaid.initialize(config);
window.mermaid.init(undefined, document.querySelectorAll('.language-mermaid'));
</script>

</html>

### Two Model Process

```mermaid
graph LR
A[Dataset with Treatment = 0 ] ----> B((Model 1 Classifier))
C[Dataset with Treatment = 1 ] ----> D((Model 2 Classifier))
B --> E{Uplift}
D --> E{Uplift}
```

You can check out my other repositories here: [Github](https://github.com/rahul-adwani?tab=repositories)
You can contact me here: [LinkedIn](https://www.linkedin.com/in/rahuladwani/)
If you like the content, please give it a star

Thanks for reading,
Rahul Adwani
