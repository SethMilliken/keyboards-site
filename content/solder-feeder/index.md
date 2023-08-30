---
title: Bespoke Handheld Solder Feeder
---

## Bespoke Handheld Solder Feeder

### Precis

A tool intended for use when soldering small electronics, designed to facilitate feeding solder wire to a workpiece smoothly, evenly, unbent, and unobstructed. And which can be assembled from cheap, easily obtainable parts.

![solder feeder](./solder-feeder.png)

### Background

When soldering keyboards, I had been finding it awkward to get the solder wire from its large spool to different locations on the workpiece, especially when soldering hotswap sockets. At some angles I could not easily pull the solder, or I would pull too much of it, and would regularly have to reposition the wire or put down the iron to sort things out. Once I had finished soldering, I would then have to wind some length of solder wire back onto the spool as part of cleanup.

I was also interested in finding a more portable soldering setup that did not rely on the particular arrangement of the soldering station in my office in order for me to solder effectively.

With these things I mind, I set out to discover whether any such tools existed for electronics soldering.

### Prior Art

- **[TIG welding pen holders](https://www.amazon.com/Clarke-Brothers-Tig-Welding-Holder/dp/B08XYDFTMG)**: This is an example of a tool used in TIG welding. But none of these holders appeared to be designed to accommodate the small diameter of solder that I predominantly use (0.5mm). These holders also do not help with the problem of where to put the spool of solder to keep it simultaneously easily accessible but also out of the way. I may eventually try one out with some modifications, but for now it does not look promising.

- **[Fly tying tool](https://www.amazon.com/dp/B07K2T87JG)**: This is an example of a tool used in tying flies for fishing. It has many of the characteristics I was looking for, and it turned out to work fairly well for the purpose. But the lack of a tapered tip made it less comfortable to use. And it was not well-balanced when used for feeding solder. But one of these might make a great budget version of the solder feeder for some.

- **[Pen Solder Feeder Hack](https://www.instructables.com/Pen-solder-feeder-hack/)**: This one was incredibly simple in concept. Get a mechanical pencil with the feed button on the side, remove the eraser top, and replace the graphite leads with your solder wire. The only mechanical pencil I could find that fit the description in the article was the [Pentel PD235A](https://www.amazon.com/dp/B007XZVVBC). I ordered one and tried it out. It worked with my leaded solder, but did not work with my unleaded solder (ostensibly the same diameter). But even when it did work, it did not work well. I had to press the button many times in a row to get the solder to advance a useful distance, and sometimes it would not actually pull the solder from the spool. And this approach also didn't help with the problem of where to put the spool of solder in the first place. Unreliable, slow, and frustrating.

- **[A Simple One-Handed Solder Feeder](https://hackaday.com/2023/07/27/a-simple-one-handed-solder-feeder/)**: This article talks about [a 3D-printed design](https://hackaday.io/project/185813-one-handed-manual-solder-feeder) that puts a spool to hold the solder wire at one end of a pen-like shaft, adds an opening in the base of the shaft to move the solder with a thumb, and a ferrule at the tip to guide the solder. It looked promising, but I do not have a 3D printer nor easy access to one, so pursuing this solution was not particularly appealing.

   While looking at this one, I was also a little taken aback at how many of the comments on this article ridiculed the very existence of such a tool. This prompted me to spend some time working on my technique.

- **Technique**: Aside from occasional hints in some of the condescending comments left about these tools, I have not found any good resources describing _how_ to properly hold and feed solder wire when soldering electronics. Most videos of people soldering focus on a closeup of the workpiece, not on the hands holding the iron and solder. And no one I found even _talked_ about this aspect.

    It was clear to me that more experienced folks had either developed and internalized specific techniques that addressed the problems I was having, had acquired fancy (and expensive) _automatic_ solder feeders, or simply were not bothered by some aspects of the process that bothered me. I experimented with different approaches, but did not arrive at any clearly superior methods. Regardless of what I tried, I continued to run into situations where I had to put down the iron or awkwardly attempt to manipulate the solder wire into the correct position.

### Bespoke Design

Unsatisfied with the prior art, I decided to create my own tool. I had plenty of fasteners and parts of various shapes and sizes on hand. And now I had some ideas to work with as well. I found a cheap ballpoint pen, disassembled it, and used the bottom half of it as the base of the tool. I used a sewing bobbin to hold the solder. And after assembly and some experimentation using it, added another arm to the tool to help keep it stabilized when in use. Here is what I came up with:

![bespoke solder feeder prototype](./solder-feeder-prototype.png)

Satisfied with the general design of the prototype, I added some refinements, upgraded some of the parts, and came up with a few alternative builds of the tool.

![solder feeder family](./solder-feeder-family.png)

The one I prefer is relatively simple, adjustable, balances well in the hand, and stays out of the way when I am not using it, allowing me to use most of my hand normally without having to put down the tool.

![preferred solder feeder](./preferred-solder-feeder.png)

### Bill of Materials

- [ ] 1x bottom shaft of ballpoint pen (or other narrow diameter, 3-4" length cylinder, preferably with one tapered end)
  - [black; 2 @ $11](https://www.amazon.com/gp/product/B07D98KYFD/)
- [ ] 1x 1" diameter sewing bobbin (or other small spool)
  - [plain; 12 @ $7](https://www.amazon.com/dp/B0CDH3J1XT/)
  - [solid aluminum; 10 @ $8](https://www.amazon.com/dp/B07X5MKCVF/)
  - [black; 10 @ $9](https://www.amazon.com/dp/B07WDBH3QD/)
- [ ] 2x 3/8" nylon cable clamp (make sure these match the diameter of the shaft you selected)
- [ ] 1x 1/2" nylon cable clamp (make sure these match the diameter the tips of your index and middle fingers)
  - [black or white; variety pack $12](https://www.amazon.com/Bigtrans-Plastic-Fasteners-Assortment-Conduit/dp/B08TVMLP9W/)
  - [white; 200 @ $12](https://www.amazon.com/XLX-200pcs-R-Type-Fastener-Plastic/dp/B01M7R2ANB/)
  - [white; 50 @ $6](https://www.amazon.com/Rierdge-Mounting-Management-Stainless-Included/dp/B097D67BFQ/)
  - [black rubber lined metal; variety pack $24](https://www.amazon.com/dp/B08BC6DYJG/)
- [ ] 2x 2.4" x 0.6" mending plate
  - [black, 12 @ $12](https://www.amazon.com/gp/product/B09XQ5CQGX/)
- [ ] 1x M4 20mm machine screw
- [ ] 3x M4 8mm machine screw
  - [black or silver; assortment that includes nuts and flat washers, $23](https://www.amazon.com/gp/product/B08SQGQJ36/)
- [ ] 3x M4 nut
  - [black; acorn nut, assortment, $10](https://www.amazon.com/gp/product/B08J3X8ZF4/)
- [ ] 1x M4 knurled thumb nut
  - [black; 10 @ $8](https://www.amazon.com/gp/product/B09T39MKYH/)
- [ ] 3x lock washer (optional)
  - [black; assortment $12](https://www.amazon.com/gp/product/B09XHVN57X/)
- [ ] 1x nylon flat washer (optional)
  - [black; assortment $12](https://www.amazon.com/gp/product/B07KQVNQ95/)
- [ ] 4x rubber feet (optional)
  - [black; 25 @ $15](https://www.amazon.com/gp/product/B07V1K32NH/)


### Bobbin Holder Assembly

This part holds the bobbin of solder wire above the open end of the shaft, so that the wire can feed directly into the shaft.

1. Wrap one cable clamp around the top part of the shaft (the clamp size depends on the diameter of the shaft).
1. Insert an 8mm machine screw through a mending plate hole, through the holes of the cable clamp, through a lock washer (optional), and cap with a nut (can use any of: a regular nut, acorn nut, thumb nut, or regular nut nestled inside a rubber foot).
1. Tighten the fastener such that the mending plate arm can be moved in the joint, but stays in place otherwise.
1. Insert a 20mm machine screw through the other mending plate hole and fasten on the other side with a regular nut. Cap the screw with a knurled thumb nut. This is the axle for the bobbin which will spin between the regular nut and the thumb nut, so you could put the bobbin on now if it is ready.

![completed bobbin holder assembly](./completed-bobbin-holder-assembly.png)

### Stabilization Assembly

This part provides a ring to fit over a finger (typically your pinky) to stabilize the tool in a balanced position and provide control when you are using it, and to keep the tool readily available when you are not using it.

1. Wrap one cable clamp around the bottom part of the shaft (the clamp size depends on the diameter of the shaft).
1. Thread an 8mm machine screw through the holes of a reversed 1/2" cable clamp and then into the holes of the wrapped clamp (the flat parts of the cable clamps should be back-to-back), then cap the end with a nut (acorn nut or thumb nut recommended).

![completed stabilization assembly](./completed-stabilization-assembly.png)

### Preparation

Wind solder from a larger spool onto a bobbin. Try to keep it relatively tight and evenly distribute the wire across the barrel as you go to prevent bulges. Mount the bobbin onto the bobbin holder arm by removing the thumb nut, placing the barrel of the bobbin over the machine screw, and then replacing the thumb nut. Make sure the bobbin can rotate freely, but you may want _some_ tension to keep the solder wire from unraveling. If necessary, adjust the bobbin holder arm so that the bobbin sits directly above the open end of the shaft, with an unobstructed path for the wire into it.

Thread solder wire from the bobbin through the shaft and out the other end, leaving about 1cm protruding. Tighten up any slack at the bobbin.

### General Use

Slip the open cable clamp ring onto your pinky with the tool inside your cupped hand. The tip of the tool should be about level with the outside edge of your index finger.

![holding demo](./holding-demo.png)

Turn your palm face down, angling the tip of the tool towards your workpiece.

![angle for use demo](./angle-for-use-demo.png)

Curl your index finger and pinch the protruding solder wire with your thumb. Pull away from the tip to feed solder. If it is awkward to pull or the solder bends when you do, adjust the placement of the ring on the shaft or the angle of the shaft until you can smoothly pull solder wire from the tool. This may also take a little practice to get right.

![feeding demo begin](./feeding-demo-begin.png)
![feeding demo end](./feeding-demo-end.png)

### Other Notes

- You may want to use different colored bobbins for different types of solder. I use black for unleaded, plain for leaded.
- You may need to adjust the placement and angle of the arm and ring assemblies depending on the size and proportions of your hands.
- The tool feeds at a rate of about 1" of wire per pull (may vary with the dimensions of your hands).
- Weighs ~65g (with full bobbin of solder)

### Budget Options

I already happened to have a lot of these parts already on hand from other projects, so they were essentially free for me. But if you don't already have boxes of assorted fasteners, you may be able to save money by getting smaller counts or substituting similar parts.

- You might be able to find other suitable screws, nuts, and washers sitting around your house, a friend's house, or could pick them up cheaply _a la carte_ at a hardware store.
- You don't necessarily need washers, a knurled thumb nut, or rubber feet at all. These just keep the assembly securely fastened and more comfortable to hold and use. Loctite and electrical tape could serve similar functions.
- Instead of metal mending plates, you could use strips of stiff plastic cut to size with holes drilled in appropriate places.
- You may know someone who sews; they will likely have spare bobbins and might be happy to give you one if you ask.
