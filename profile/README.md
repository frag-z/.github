```
                                                                
      _/_/                                                      
   _/      _/  _/_/    _/_/_/    _/_/_/              _/_/_/_/   
_/_/_/_/  _/_/      _/    _/  _/    _/  _/_/_/_/_/      _/      
 _/      _/        _/    _/  _/    _/                _/         
_/      _/          _/_/_/    _/_/_/              _/_/_/_/      
                                 _/                             
                            _/_/                                
```
A multiplayer fps game made with godot, focus on gameplay, should run on any toaster

# status
Rewriting the game from scratch in c++, godot for a multiplayer fps game has become unwieldy and we need better performance. Check out the [roadmap](https://github.com/frag-z/roadmap) for more details

# rationale
A lot of work was put in for the godot version of this game, why remake it?

* I can develop the game without having to use the godot editor, meaning everything can be done from command line
* Makes automated builds easier
* Improve performance
* Have complete control over visual style, pbr materials aren't required
* We can use a typed programming language, improve debugging and testing
* Not locked into the godot engine and it's quirks

Tech Stack:
* Physics: Jolt Physics
* Networking: [enet](http://enet.bespin.org/)
* Graphics: opengl
* UI: [imgui](https://github.com/ocornut/imgui)
* logging: [spdlog](https://github.com/gabime/spdlog)


