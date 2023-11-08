## Helping developers write more secure systems code

### About Checked C

Checked C extends C with bounds checking and type-safety.  This helps developers write more secure systems code.
 * It is opt-in and backwards compatible. As a developer,  you add annotations and/or modify types to opt-in to bounds checking and type-safety. 
 * All existing C code is valid Checked C code. 
 * It supports incremental conversion of code. You can convert a few security-critical functions or your entire program, and do the conversion
   as you have time.
 * It supports annotations that can be erased from your program using macros, so that your Checked C code can compile with C
   compilers that do not understand Checked C annotations.

Checked C includes a [language specification](https://github.com/checkedc/checkedc/releases/download/v1.0/checkedc-v1.0.pdf), 
samples, a compiler, and a tool for translating your existing C code to Checked C.

## About the Project

 The language specification and compiler were developed at Microsoft from 2015-2021.  The Checked C effort 
 now continues as an active open-source research project. Recent contributions include:
 
 - The 3C tool for translating C to Checked C (Aravind Machiry, Mike Hicks and others).
  A paper on this tool appeared in OOPSLA '22 and won a Distinguished Paper award.
 - Fat-pointers for temporal safety (Jie Zhou, John Criswell, and Mike Hicks). This work
   will appear in the upcoming OOPSLA ’23 conference.
 - Support for erasing annotations for C compilers that don’t support  Checked C (in progress).
 -  Experiments with converting open-source systems code.
 
 As of 2023, we're officially a non-profit!  This supports continuity of the project beyond any
 one person, helps us keep track of intellectual property rights, and will let us raise funds 
 so support project activities.
 
<!--
## Learning more

## Organization of the rpos
-->
