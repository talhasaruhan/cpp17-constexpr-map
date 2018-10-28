# Constexpr string to id map at compile time
This is an illustrative sample of how easier life can be with new C++! If you want a tagging solution to resolve names to plain integers at compile time but can't bother with the hideous templates, may the constexpr be with you!

Disclaimer: Works only with Clang trunk as of time of this commit, GCC and VC++ simply fall back to run time evaluation. 
Also, there are a lot smarter examples of compile time evaluated maps. With this, I wanted to try the easiest possible implementation I could think of in 2 minutes and was amazed that Clang actually compiled it properly. 
