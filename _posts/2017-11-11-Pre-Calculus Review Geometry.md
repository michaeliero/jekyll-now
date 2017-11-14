---
layout: post
title: Pre-Calculus Review—Geometry
---
Finally beginning this. Here is my pre-calculus review, in preparation for my calculus review. Will try to put this up at some type of regular interval. I want to reiterate that I'm in no way an expert on this material—in fact, I'm probably not qualified to discuss this—but this is just my understanding of it. If you have any comments, questions, angry reactions, etc., please let me know. Here goes:

## Intro 
The hardest thing for me when it comes to math is to memorize the various rules and definitions. It's part of the language used to describe the various relationships and problems you encounter. There's no way around it, and that's especially true for this introductory material. I use Anki (Google it) to memorize concepts when necessary, but use whatever works best for you. If you use the material enough, though, you won't have to actively memorize the concepts. So, if you're so inclined, just keep playing with these concepts in your mind throughout the day, and soon they'll ljust be a part of your long-term memory.

## Geometry
### Triangles
####Sum of Angles
One degree is equal to 1/90th of a right angle. That's just the definition. Accept it. There might be a reason for this, but I don't know it. This also means that two right angles together make up 180 degrees. From this, the intuition arises that when angles form a straight line, the sum of the angles is 180 degrees (because that's what two right angles form when put together). There's probably a more mathematical way to describe this, but again I'm just an amateur, and that's how I explain it.

When a line cuts across parallel lines, then the corresponding angles are equal to each other. The alternate itnerior angles are equal as well:

![Transversal Line](/images/Transveral%20Line%20and%20Angles.png)

This line that cuts through the parallel lines is called a "transversal."

From this, we can conclude that the sum of angles in any triangle is 180 degrees. Here's the proof:

![Proof for 180 Degrees Triangles](/images/Proof%20for%20180%20Degrees%20for%20Triangles.png)

This means that the sum of the acute angles in a right triangle is 90 degrees (because the right angle is itself 90 degrees, and that leaves 90 degrees left for the two other angles to fill in).

Finally, in any triangle, an exterior angle equals the sum of the opposite interior angles:

![Exterior Angle](/images/Exterior%20Angle.png)

Here's my informal proof for this:

$$
	C + D = 180 \text{ degrees} \\
	A + B + C = 180 \text{ degrees} \\
	A + B + C = C + D \\
	A + B = D
$$

#### Area

The area for an arbitrary rectangle is \\(A=hb\\), where A = area, h = height, and b = base. Don't have a proof for this—just accept it.

The area of a right triangle is \\(A = \frac{1}{2}hb\\). Again, just something you have to accept, though I'm sure there's a formal proof relating to the area of a rectangle—any arbitrary right triangle can be half of any arbitrary rectangle that is divided by a diagonal line, so it makes that the area of that right triangle would be half of that rectangle. 

Any triangle can be viewed as the sum or difference of two right triangles:

![Area of Triangles](/images/Area%20of%20Triangles.png)

If the base of a triangle is held fixed and the upper vertex is moved back and forth across a parallel line, then the area of that triangle doesn't change.

![Fixed Area Triangles](/images/Fixed%20Area%20Triangles.png)

This makes sense when you think of the fact that the height and the base don't actually change when you move that upper vertex. The only things that change are the angles and the lengths of the sides, not the area.

####Similarity

Two triangles are similar if they have have the same shape but are different sizes. The precise meaning is that the corresponding angles must be equal. This implies that the ratios of their sides must also be equal.

![Similar Triangles](/images/Similar%20Triangles.png)
$$
\frac{a}{d} = \frac{b}{e} = \frac{c}{f} \\
\text{ OR } \\
\frac{a}{b} = \frac{d}{e}
$$

[Note that the triangles above aren't actually similar—I'm very bad at drawing pictures and I didn't know how to copy the one triangle and blow it up, so I just tried to draw a similar triangle. Just pretend they're similar according to the definition]

If two triangles are similar, then the ratio of any two sides of one triangle equals the corresponding ratios of the other sides. It's about the *ratios*
for the sides.

Note that two triangles are necessarily similar if two pairs of corresponding angles are equal. This makes intuitive sense, given that if two of the angles are equal, and if the sum of the three angles will be 180 degrees, then the size of the third angle will be determined once you're given the two other angles.

Also, the ratio of areas between two similar triangles equals the ratio of the squares of any pair of corresponding sides.

Proof:
$$
A_1 = \frac{1}{2}h_1b\\
A_2 = \frac{1}{2}h_2e \\
\frac{A_1}{A_2} = \frac{\frac{1}{2}h_1b}{\frac{1}{2}h_2e} = \left( \frac{h_1}{h_2} \right) \left( \frac{b}{e} \right) = \left( \frac{b}{e} \right) \left( \frac{b}{e} \right) = \frac{b^2}{e^2}
$$

This makes intuitive sense too. Since the ratio of the sides would be \\(frac{b}{e}\\), it would make sense that the ratio of the areas would be the the same as the ratios of the squares of the sides too. The ratio of the sides would be relevant, but when it's squared, it puts the side ratio in the same dimension as the area ratio. [If that makes sense—it's not a formal mathematical statement, just something I observed and think is an interesting connection.]








