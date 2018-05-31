Light Field reconstruction is a relatively new technique for 3D reconstruction and rendering, that can be used to compute the depth of objects from a particular scene (physical subspace) given a set of images from different viewpoints. This technique has gained a lot of interest in the last ten years due the applications to Virtual and Augmented Reality; reflected most recently on the acquisition of the company Lytro (Light Field Camera Developer) by Google on [March of this year](https://www.theverge.com/2018/3/21/17148622/google-lytro-acquisition-light-field), and the recent advances presented also by [Google](https://www.blog.google/products/google-vr/experimenting-light-fields/) and [Magic Leap](https://www.wired.com/story/magic-leap-lightwear-headset-hardware/) for Light Field Applications on the new VR media revolution. Industrial interest also carries tipically development closure and Light Field is not an exception.

Inspired by the open source spirit (characterizing the julia Comunity) and the search of interesting applications for the julia package [Shearlab.jl](https://github.com/arsenal9971/Shearlab.jl), developed by me and presented at the last JuliaCon), I developed a julia library for Light Field reconstruction that optimizes the computation by using the Shearlet transform to represent sparsely the Light Field, called [LightFields.jl](https://github.com/arsenal9971/LightFields.jl). In this lightning talk I will present thebasics of the LightFields.jl's API and also a very easy and cheap, open hardware implementation of a Light Field Camera using no more than julia and a Raspberry Pi.
