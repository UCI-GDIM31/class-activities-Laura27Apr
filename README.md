# in-class-activities
## Devlogs
### W1
Hello World!

### W2
The reason that r, g, b variables floats is that the color section in the Unity is set from 0 to 1.0, therefore the value will be fractional number instead of whole numbers, text or true/false decision;
The bounce variable should be the whole number because there will not be any bounce times like 0.5. And of course the value of the bounce cannot be the text or true/false decision;
For the step four, the useful information is that this line need to add the semicolon to make this line completed.

### W3
#10
We would make the parameter (input) "int" since the choice is based on the player¡¯s current friendship level, which is a whole number value; and the return type (output) would be "boolean" since the requirements of this step is that to make the response "tells you whether or not", which is a true/false judgement.

1. Classes are like the ingredients of a plate to make a cake. and the Component is the cake. We use ingredients (classes) to make and form the cake (Component).
2. This is because as the ball bounces again and again, the times the ball multiplies the GetColorMultiplier again and again. In this scenario, this value increases exponentially, and the ball's brightness grows ever brighter.

### W4
#10
In line 5, the code defines the _movespeed and allow it to be view and edit in the inspector of the Unity;
In line 22, the code uses a function to have a value and save it into the translation;
In line 25, the code calls the translation method on the translate may to move the transform in the direction and distance of translation.

#10
1. Since the cat and ball need to collide with each other, both of them need rigidbody. The goal need to let the ball get through, so it will be checked the "IsTrigger".
2. At first, my cat was "floating" and it just looks like the cat is walking on the space. We first tried to cancel the rigidbody on the cat, then we found that the cat cannot hit the soccerball with it front legs. And we tried to check IsTrigger on the cat, and the cat just walk through the soccerball. Then finally after asking the professor, we found that the problem is that the collider on our cat is to big. Then we make it smaller and it does not float anymore.

### W5
Q: Can we use "GetComponent" without save it into a variable (definition)?
A: Of course we can. But this is not that efficient if you are using it for more than once since this method re-looks up components every time, which wastes performance when placed inside Update().

Plan for DeerW5:
First, build the class for the DeerW5. Then define the variable, and here the variable is _destination. We need to use the Start() method, which is provided by the Unity. And we need to call GetComponent to get the NavMeshAgent on the deer. Then we need to call the SetDestination to give the destination for the deer to move to. This method needs to make the deer automatically walk to the assigned destination, which is the cat here when the game starts.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 