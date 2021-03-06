# 3dprinted-mask
Here is workflow we developed to produce a 3D printed respirator mask.  This mask uses the base mask from the "Montana Mask" project. See [https://makethemasks.com](https://makethemasks.com) for more information.


<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/button_hole_all4.jpeg">
</p>


## Disclaimer
>It's common to think that a homemade mask covering your face and nose protects you from catching anything. This isn't necessarily true.  A mask, can possibly do two things: 

>1. Protect other people from you. Should you sneeze or cough, something covering your mouth and nose will act to stop your expelled droplets from becoming airborne and possibly being inhaled by someone else.  This is mostly what a homemade mask does.

>2. It is harder to achieve a mask that will prevent you from inhaling something airborne that you may encounter.

>We do not know if this mask does either. This project is a workflow consisting of various resources we pulled from around the Internet that results in a mask that you can wear and reuse. The eventual mask seal is pretty good, to the point that your breathing action will be noticeably modified when wearing the mask. It will be clear to you that your inhaling and exhaling will mostly be forced through the filter material. What precise action the filter accomplishes on 1 or 2 above, we don't know. 

---

### Part I: The Mask Parts
To begin, download two STL files, [the mask](https://www.makethemasks.com/s/MontanaMasks.stl), and the [filter holder](https://www.makethemasks.com/s/MontanaMaskFilterFrameWithFlange.stl). 

Print them both on a 3D printer. If you don’t have a 3D printer, or have thought about buying one, now is a great time.  We’d recommend [this one](https://shop.prusa3d.com/en/3d-printers/181-original-prusa-i3-mk3-3d-printer.html#) or [this one](https://shop.prusa3d.com/en/3d-printers/994-original-prusa-mini.html#).  

For printing, PLA material is fine with 10% infill. If the mask is sliced with the front square (“air in”) side down, no supports will be needed.  Combine the filter holder and mask in the same print job (arrange them on the build plate in the slicer software). It’ll take about 7 hours to complete. The default size is large. Scale down (in your slicer) to 90% for medium and 80% for small. Here’s what you’ll get.

<p align="center">
   <img src=https://github.com/tbensky/3dprinted-mask/blob/master/Images/mask800.JPG>
</p>


If you are concerned with the "porosity" of 3D printed parts, you can seal the mask with some silicon sealant (spray? paint on liquid?)

In use, the mask may be washed or wiped with bleach wipes.

### Part II: Fitting the mask
Immerse the face side of the mask in boiling water for 30 seconds or so, as shown here.

<p align="center">
   <img src=https://github.com/tbensky/3dprinted-mask/blob/master/Images/mask_water.JPG>
</p>

This won't melt the plastic (you'll need 215C for PLA, boiling water is 100C) but will make it soft and bendable.

Push the mask lightly against your face, and pinch it (lightly), mostly around your nose and cheeks, so it loosely fits the contours of your face. Do not pinch it tightly at this point, as this is not the final fitting. Just adapt it somewhat to your face. The final seal is coming (below).

### Part III: Seal
Get some 5/16” D-shape weatherseal tape ([Home Depot link](https://www.homedepot.com/p/Frost-King-5-16-in-x-1-4-in-x-17-ft-White-D-Center-EPDM-Medium-Gap-Weatherseal-Tape-V25WA/100017014)). Here’s what it looks like. You can see the “D” shape. The yellow strip is peeled away, exposing an adhesive layer. Use a rubber seal like this stuff, not a foam one.

<p align="center">
   <img src=https://github.com/tbensky/3dprinted-mask/blob/master/Images/D-shape.JPG>
</p>


Work one continuous piece of the tape into the inner perimeter of the mask, like this.

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/D-shape_start copy.JPG">
</p>

When done carefully match the two ends.

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/D-done.JPG">
</p>

### Part IV: Final Fitting
Again place the mask in boiling water for 30 seconds or so, and now push it firmly against your face.  Pinch all sides inward toward your nose and cheeks, so the mask is tight and snug, and also comfortable.  The adhesive on the weatherstrip will hold up in the hot water, but you might have to press the weatherstrip against the mask again, to firm it up again.

Optional: When done, you can add a line of [silicon sealant](https://www.homedepot.com/p/DAP-Silicone-Max-2-8-oz-Clear-100-Premium-Kitchen-and-Bath-Silicone-Sealant-08794/301531803) in the small gap between the weatherseal and plastic.


### Part V: Attachments
Next, decide how you want to attach the mask to your face.  You can tie elastic to the holes, like this:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/elastic_ties.jpg">
</p>

We found the masks hard to adjust this way, so we made a T-shaped add-on that allows one to use button-hole elastic. Here’s the adapter (design file [here](https://www.thingiverse.com/thing:4283952)):

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/T320.jpeg">
</p>

It goes into the mask like this:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/button_hole.jpeg">
</p>

In case you don’t know what “button-hole” elastic is (we didn’t), it’s elastic with evenly spaced slits cut it in, like this:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/button_hole.JPG">
</p>

With the T-shaped adaptor and the button hole elastic, attachment and adjustment is very easy.  You’ll need four such adapters that fit into the mask’s existing holes (with a dab of super glue or hot glue from a glue gun) to hold them.  This will be an additional 3D print job, with a print of 4 of them taking 45 min. No supports are needed, and we used 10% infill.



### Part VI: Filter
This is the part with the most debate out there: what material to use as a filter. Whatever you use, you only need a piece a bit larger than the plastic filter holder you printed, like this:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/filter_fit.JPG">
</p>

It’ll push firmly into the opening, from inside the mask like this:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/filter_fit_mask.JPG">
</p>

#### Filter Materials

Here’s what we’ve learned about materials.

Ideally, you’d like to use some N95 material, but this is in short supply. If you have a mask made of N95, you can cut up the mask and get many uses out of the material itself (as an insert for this mask), instead of just one (one use per medical mask).

If you do not have an N95 mask, vacuum cleaner bags will work for this, as outlined [here](https://smartairfilters.com/en/blog/best-materials-make-diy-face-mask-virus/) (see graphs) and [here](https://www.ncbi.nlm.nih.gov/pubmed/24229526). You can start with common bags like this one, which claims to filter down to 2 micrometers.

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/kenmore.JPG">
</p>

A virus however, is <1 micrometer, so we’ll have to do better. HEPA vacuum cleaner bags like these

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/meile_filters.JPG">
</p>

claim to filter to this level, and they’re [available](https://www.bedbathandbeyond.com/store/product/miele-airclean-fjm-dustbag/1016438286?keyword=meile-baggs).  It turns out that N95 masks and these HEPA vacuum cleaner bags seem to be made from similar materials as shown [here](https://youtu.be/ZWkLqJrjWe8).  

There is more debate out there, as some air filter bags can be made of fiberglass, the fibers of which you don’t want to inhale.  The Miele bags above appear to be made from polymer fibers (i.e. not glass), but you still don’t want to breathe them.  You can ease concerns in this way: 

* Add a layer of cotton material (T-shirt, bandana, etc.) or some of the 2 micron vacuum cleaner filter around the HEPA filter. These are to be added on the “mouth side” of the filter assembly. Here’s a layer of the 2 micron material being peeled away from the bag:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/2micron.JPG">
</p>

* Be sure the fibrous side of the HEPA filter faces outward on your mask, and the smooth bag side faces inward, toward your mouth.

We do both. 

#### Filter installation

Here’s vacuum cleaner bag,

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/vac_bag.JPG">
</p>

which we cut it up into as many squares as we could, sized just a bit larger than the filter holder as shown here:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/filter_fit.JPG">
</p>

Note the fibrous side is down/outward, and paperish “bag” material is inward. You push the wrapped filter holder into the mask as shown here:

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/filter_fit_mask.JPG">
</p>


### Part VII: All done

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/button_hole_all4.jpeg">
</p>


### Part VIII: Tests

* As noted in [this video](https://youtu.be/CVjGCPfRwUo), a standard test is to push the mask against your face, sealing the filter hole with your hand, then exhaling strongly, and noting any outward leaks under the seal. Adjust as needed, including warming to morph the plastic.

* Once sealed, you can try sniffing common scents and see how the mask performs.  Examples: extingish a candle, a perfume mist, cooking smells, etc. We could still smell most things (less so though) both with this mask and a professional surgical mask, noting that these are intense concentrations of smells.

### CO2 tests

An <a href=https://www.sparkfun.com/products/15112>SCD30 CO2 sensor</a> was installed inside of the mask while it was being worn.  Normal breathing while in the sitting position was done
for about 250 seconds, for both the 3D printed mask, and the N95 mask. 

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/mask_sensor.jpg">
</p>




CO2 concenctration as a function of time are shown here.

<p align="center">
   <img src="https://github.com/tbensky/3dprinted-mask/blob/master/Images/co2_both.png">
</p>

Fresh, outdoor air has a CO2 concentration of about 400 ppm, while both masks seem to maintain a CO2 concentration of around 20,000 ppm (50x outdoor air).



### Resources


* [https://makethemasks.com](https://makethemasks.com)

* [https://www.fixthemask.com](https://www.fixthemask.com)

* [https://engineering.rowan.edu/research-centers/mask/index.html](https://engineering.rowan.edu/research-centers/mask/index.html)

* [https://3dprint.nih.gov](https://3dprint.nih.gov)










