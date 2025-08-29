# Mist-Linux
This is a CLI based BUILD of Psyker-team's 'Mist' - Built for Linux users to add a layer of protection to their ART. Local image training Poison (Similar to Nightshade).

Where the hell is the love for Linux Artists after all?

Really - Why should our artwork go unprotected just because WE chose freedom, security and privacy when picking our OS? 
Nightshade devs should be giving us a Linux build so we can all be team Nightshade and make that project stronger.
Instead, here's the next best thing:

I built Mist for Linux. There are builds for Windows and Mac but not offically for Linux, so here you go.

While Mist is not a full replacemnent for Nightshade, it is certainly comparible to how Glaze protects your images.
And while Mist cannot fool training into seeing the wrong thing, it will not clearly reproduce it.

# The Difference between this and Nightshade:

Unlike Nightshade, Mist cannot fool a database into seing a cat when it sees a dog. This is more like glaze where the subject is made less reproducable.
With a open and customisable system like this; we can make it harder for AI nerds to depoison. The plan is in offering unparrel customisability and randomisation algerithms.
Logic: If you use the same 'recipe' every time you poison somerthing you adversary can just the same antedope.

# Don't get cocky. It's not bullet proof.

Don't go around the art and AI community bragging about how this helps your protection, and certainly don't try to goad the AI bros.
Especially do not show a before and after image for which they can use as training to depoison.

Understand that this like any method to proect your art, is not PERFECT. Just like with Nightshade, your work is not invulnerable from a highly skilled AI artist.
I still recommend you use this in combination with HTML bot detection and hyjack as well as good old fashioned watermarks and licensing disclaimers. 

Lastly... this is in it's infancy and it's experirimental. I just CANNOT guarrentee that this will protect your art so...

Keep remain deligent.

# I don't like this because it requires AI models

I know right? But... So does Nightshade. So does Glaze. 

Yes this means your works are more likely to be detected as AI, but that in turn is what protects your true artwork - YOU ALONE have the original perfect copy. That can hold up in court. 

# Why CLI, why not GUI based?

Simple: I wanted this to run inside of Krita. I don't want artists to have to go to yet another app.

-

# Source:

https://github.com/psyker-team/mist-v2

# Build Environment

OS / Kernel: Nobara Linux 42 • Kernel 6.16.2 • x86_64

CPU: Intel i9-13900HX (AVX2 / AVX-VNNI support)

Memory: 31 GiB RAM

GPU: NVIDIA RTX 4090 Laptop (CUDA 13.0, driver 580.76.05)

Compilers / Toolchain:

GCC 15.1.1

Clang 20.1.8

glibc 2.41

CMake 3.31.6, Ninja 1.12.1, Meson 1.7.2

Python 3.13.5

Graphics APIs / SDKs:

CUDA toolkit + OpenCL ICD (NVIDIA)

Vulkan 1.4.x (NVIDIA + Mesa)

OpenGL 4.6 (Mesa / NVIDIA)

Key libs: Qt5 (5.15.17), Qt6 (6.9.1)

----


