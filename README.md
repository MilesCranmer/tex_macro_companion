# tex_macro_companion
A "vim-companion" program that automatically generates macro's for you on the fly based on sequences that you use a lot in LaTeX.

E.g., if you write `\mathcal{S}_{S/N=10}^{3\text{ ms}}` 2 times, it will spit out a macro for you and do a search and replace.

Could also be extended to other languages with macros, such as C++. 

It would be wise to impose some lower limit on the number of characters, e.g., 10-chars, before generating the macros.

Picking the name for the macro would be difficult. This could be randomly generated, or maybe some substring based on detex-ified string of the above, and based on what commands are still available in the namespace.
