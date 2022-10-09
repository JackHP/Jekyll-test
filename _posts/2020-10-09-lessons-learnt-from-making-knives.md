---
title: "Lessons Learnt From Making Knives"
categories:
  - JHP Knives
tags:
  - knives
---
{% include figure image_path="/assets/images/Parametric.PNG" alt="A screenshot from Fusion 360"%}
### Lesson 1: Manufacturing Process Affects Material Properties

A few years ago I started making chef knives by hand. It's a long process that requires full attention throughout, as even a small lapse in concentration can lead to an irreparable blade.

{% include figure image_path="/assets/images/IMG_20180418_164002392.jpg" alt="Sheets of steel with waterjet cut knife blanks cut out of it"%}

The stock steel comes as large flat sheets and from here, blanks are water jet cut. Early on I realised that there were problems with simply taking one of these blanks and grinding it to shape. When I sent some of them off to be hardened I got a call back from the heat treater. He told me that they had all warped and explained to me that this is because the steel would have originally been wound into a large coil from the steel mill and that the process of unwrapping it induced stress into the material and this was now causing the knife to spring back into that original starting shape.

{% include figure image_path="/assets/images/hot-rolled-steel-coil-1.jpg" alt="Roles of steel"%}

From that moment onwards, I had the blanks heat treated first and then I would grind them to final shape whilst hard. There was still some minor warping but I could account for it as I ground the metal away. This let me make perfectly straight blades but now I had to be extra careful to ensure I didn't over heat the steel and temper it to the point where it no longer held an edge.

### Lesson 2: Completely “Hand Made” is Slow and Repetitive 

I love to use my hands to make things but learned that making knives this way is very slow and repetitive. So, I started to think about how the process could be sped up and still allow me to be creative and produce a high quality knife. Fast-forward two years, I enrolled at Portland Community College in the US to study machining and had been teaching myself Fusion 360 to complete the class projects. I also have access to a HAAS VF-2 CNC milling machine. This meant I could now start modelling the chef knives in CAD, generate tool paths for CNC and run them directly on the HAAS. Making them with a CNC machine and not having to grind hardened steel by hand for hours on end is definitely the way to go.

Using Fusion 360 and a CNC mill also let me expand on the types of products I could make. In the one product I could have my original knife design and use this to experiment with boxes/ handle designs and seamlessly transition to creating the necessary toolpaths to bring these virtual models to the real-world - all the while costing me nothing as a student.

### Lesson 3: Fixtures and Work Holding Need Careful Consideration

I already had hundreds of dollars worth of pre-cut knife blanks, so I had to use these up first. As the knife had some fairly complex 3d curves on the cheeks of the blade, I used parametric modelling within Fusion to cut down time involved with making adjustments and prototyping a machined version of the knife that matched the hand-made version as close as possible. Designing everything parametrically also let me update all the tool paths automatically without any extra work, further cutting down on R&D time.

{% include figure image_path="/assets/images/hot-rolled-steel-coil-1.jpg" alt="Roles of steel"%}

With the knife now modeled, I needed a way to hold onto it within the machine and had originally considered using soft jaws - some replaceable jaws for a vise that are machined to match a non-standard shape. The steel is only 0.110" (~2.8mm) thick and I knew that this would mean that the chance for chatter when cutting was high. I don't have access to a vacuum table or a magnetic chuck so this meant the only option I had to hold onto the knives was to use a tape and glue fixture - a technique that is excellent for machining a few parts that are very thin and hard to hold onto.

If I was starting from scratch again I would have  some square stock to begin with. I could have made a simple fixture that clamped them down, just as an inspiration of mine does, [Aaron Gough](https://www.youtube.com/watch?v=JxAH6TGgNSA&t=145s).

The beauty of having the parametric CAD model is I could quickly iterate on fixture designs by booleaning out the shape from stock then creating toolpaths. I used the same process when designing the box to put the knife in when complete. Having this all in one program really helped.

{% include figure image_path="/assets/images/hot-rolled-steel-coil-1.jpg" alt="Roles of steel"%}

### Lesson 4: If Quality Matters, Control as Much of the Process as Possible

In the video below, you can see what this machining looks like, but what it doesn't show is what happened to some of the knives after they came off the fixture. Many of the knives warped like a Pringle. Even though I had machined material equally from both sides of the knife, there was once again issues with stress from the rolling process that steel goes through coming back to haunt me. The issue was that when these knives had been sent off for heat treatment they had only been hardened and tempered when they really should have gone through multiple normalisation cycles to relieve the stress in the material.

When it comes to making thing like boutique one-of-a-kind knives, understanding and having some level of control of each process is vital. Everything from the initial design, materials, heat treating, machines used etc. can have a dramatic impact on whether the final product will come out as intended.

{% include video id="VC08jo6Cw8c" provider="youtube" %}

This is the final product and what a knife with both sides machined looks like:

{% include video id="k0x-FNVTRMI" provider="youtube" %}
