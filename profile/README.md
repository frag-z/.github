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

# organization
This organization contains many smaller repositories, the goal is to make the project modular and then include repositories as submodules of others so that we can independently test and work on components easily.

The main tool that facilitates this is [`ngpm`](https://github.com/cuppajoeman/selective-submodule-cloner), which we can clone in with:

```
git clone git@github.com:frag-z/nested-godot-project-manager.git
```

In order to manage which submodules get cloned in we will use the [`selective-submodule-cloner`](https://github.com/cuppajoeman/selective-submodule-cloner)

```
git clone git@github.com:cuppajoeman/selective-submodule-cloner.git
```
