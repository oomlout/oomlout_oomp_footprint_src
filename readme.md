# oomlout_oomp_footprint_src


## notes

### oomp_key

* oomp_key -- oomp{owner}{library}{footprint_name} 
* oomp_key_extra -- oomp_footprint{owner}{library}{footprint_name} 
* oomp_key_full -- oomp_footprint{owner}{library}{footprint_name}{md5_6}
* oomp_key_simple -- {owner}{library}{footprint_name}  

## actions

* action_setup -- pulls the folder details from kitspaces directory and adds all the found repos to repo.yaml. Then clones all the repos one by one and copys the footprints to various directory structures. Then adds a yaml file for each with details and puts a readme.md in the folder with the details printed out.