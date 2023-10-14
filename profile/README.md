```
                                                                
      _/_/                                                      
   _/      _/  _/_/    _/_/_/    _/_/_/              _/_/_/_/   
_/_/_/_/  _/_/      _/    _/  _/    _/  _/_/_/_/_/      _/      
 _/      _/        _/    _/  _/    _/                _/         
_/      _/          _/_/_/    _/_/_/              _/_/_/_/      
                                 _/                             
                            _/_/                                
```

# status
Working on performance improvmeents check out the [roadmap](https://github.com/frag-z/frag-z-organization)

# organization
This organization contains many smaller repositories, the goal is to make the project modular and then include repositories as submodules of others so that we can independently test and work on components easily.

We use git submodules to do this, so after a cloning a repository the command you'll want to use is:

```
git submodule update --init --recursive
```

Note that when you open a godot project that uses other godot projects as dependencies, it will complain because it only allows one `project.godot` file in the root directory, to solve this we've created a script which can store and restore all the `project.godot` dependencies easily.
