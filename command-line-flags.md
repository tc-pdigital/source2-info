- [Summary](#summary)
  - [tier0.dll](#tier0dll)
  - [vrad3.exe](#vrad3exe)
  - [engine2.dll](#engine2dll)
  - [resourcecompiler.dll](#resourcecompilerdll)
  - [materialsystem2.dll](#materialsystem2dll)
  - [rendersystemdx11.dll](#rendersystemdx11dll)
  - [rendersystemvulkan.dll](#rendersystemvulkandll)

# Summary
Below are the command line flags gleaned by disassembling the following binaries from the Half Life: Alyx Workshop Tools. 

**This list is incomplete and may contain duplicates/missing flags.**


tier0.dll
---
> This library is loaded by all assemblies in the engine, therefore the flags listed below should apply to all executables used by the tools.
                    
| **Flag**                     | **Effect**                                                                                    |
| ---------------------------- | --------------------------------------------------------------------------------------------- |
| vminidump_exception_code     | Unknown                                                                                       |
| testmode                     | Unknown                                                                                       |
| stealthdebugger              | Unknown                                                                                       |
| start_resource_profiling     | Unknown                                                                                       |
| retail                       | Force engine to run in retail mode.                                                           |
| profile                      | Unknown                                                                                       |
| phased_window_create         | Unknown                                                                                       |
| nominidumps                  | Unknown                                                                                       |
| noloaderlockprobe            | Unknown                                                                                       |
| nohibernate                  | Unknown                                                                                       |
| nodump                       | Unknown                                                                                       |
| nocustomermachine            | Enable Valve internal features. Also enables physics tool in hammer, and Source 1 MDL import. |
| noautoargs                   | Unknown                                                                                       |
| noassert                     | Prevents asserts from being checked. **This has no affect on retail builds**                  |
| no_assert_dialog             | Forces asserts to be sent to stdout. **This has no affect on retail builds**                  |
| mpi_worker                   | **Unconfirmed:** Enables Valve MPI for distributed builds.                                    |
| minidump_log_path            | Unknown                                                                                       |
| minidump_full                | Unknown                                                                                       |
| memstackstats_keep_pools     | Unknown                                                                                       |
| inset_top                    | Unknown                                                                                       |
| inset_right                  | Unknown                                                                                       |
| inset_left                   | Unknown                                                                                       |
| inset_bottom                 | Unknown                                                                                       |
| ignorecontentasserts         | Unknown                                                                                       |
| full_memory_dumps            | Unknown                                                                                       |
| force_dpi                    | Unknown                                                                                       |
| force_battery_level_battery  | Unknown                                                                                       |
| force_battery_level          | Unknown                                                                                       |
| force_assert_sdl_dialog      | Unknown                                                                                       |
| etwprofile                   | Unknown                                                                                       |
| error                        | Unknown                                                                                       |
| enable_minidump_log          | Unknown                                                                                       |
| emaildumps                   | Unknown                                                                                       |
| disablehangwatchdog          | Unknown                                                                                       |
| disable_minidump_log         | Unknown                                                                                       |
| disable_affinity_preferences | Unknown                                                                                       |
| dedicated                    | Run engine in dedicated server mode.                                                          |
| debugbreak                   | Unknown                                                                                       |
| debug_exitprocess            | Unknown                                                                                       |
| clearassertstate             | Unknown                                                                                       |
| break_on_crash               | Unknown                                                                                       |
| assertbreak                  | Unknown                                                                                       |
| assert_content               | Unknown                                                                                       |
| assert                       | Unknown                                                                                       |
| allowmultiple                | **Unconfirmed:** Allow multiple instances of the engine. This may not work on retail builds.  |
| RESERVELOWMEM                | Unknown                                                                                       |
| PROCESSHEAPZEROMEM           | Unknown                                                                                       |
| PROCESSHEAP                  | Unknown                                                                                       |
| NOPROCESSHEAP                | Unknown                                                                                       |
| 2GB                          | Unknown                                                                                       |

## vrad3.exe
> This executable is called by resourcecompiler.exe/Hammer during a final map compile.

| **Flag**                  | **Effect**                                                             |
| ------------------------- | ---------------------------------------------------------------------- |
| threads <**num_threads**> | Force VRAD to use this number of threads                               |
| allthreads                | Unknown                                                                |
| indir                     | Unknown                                                                |
| outdir                    | Unknown                                                                |
| script <**file_path**>    | *Unconfirmed:* This is normally the path to a **.vmap** file           |
| entrypoint                | Unknown                                                                |
| sse2                      | Unknown                                                                |
| sse3                      | *Unconfirmed:* Flag to force **VRAD3** to use a particular CPU feature |
| sse4                      | *Unconfirmed:* Flag to force **VRAD3** to use a particular CPU feature |
| avx                       | *Unconfirmed:* Flag to force **VRAD3** to use a particular CPU feature |


## engine2.dll

| **Flag**                   | **Effect**                                                                |
| -------------------------- | ------------------------------------------------------------------------- |
| adapter                    | Unknown                                                                   |
| addon                      | Unknown                                                                   |
| addon_path                 | Unknown                                                                   |
| allocwarnmb                | Unknown                                                                   |
| allow_no_lobby_connect     | Unknown                                                                   |
| allow_non_tools_paths      | Unknown                                                                   |
| allowdebug                 | Unknown                                                                   |
| appidoverride              | Unknown                                                                   |
| asset                      | Unknown                                                                   |
| attachtodebugger           | Unknown                                                                   |
| avx                        | Unknown                                                                   |
| background                 | Unknown                                                                   |
| bench                      | Unknown                                                                   |
| benchframes                | Unknown                                                                   |
| benchnoexit                | Unknown                                                                   |
| benchnote                  | Unknown                                                                   |
| benchtime                  | Unknown                                                                   |
| border                     | Unknown                                                                   |
| breakimmediately           | Unknown                                                                   |
| bugvoice                   | Unknown                                                                   |
| buildcubemaps              | Unknown                                                                   |
| c                          | Unknown                                                                   |
| clientonly                 | Unknown                                                                   |
| comment                    | Unknown                                                                   |
| component                  | Unknown                                                                   |
| con_logfile                | Unknown                                                                   |
| condebug                   | Unknown                                                                   |
| conrotate                  | Unknown                                                                   |
| console                    | Open VConsole on boot                                                     |
| consoleapp                 | Unknown                                                                   |
| consolelog                 | Unknown                                                                   |
| consolelog_append          | Unknown                                                                   |
| consolelog_notimestamp     | Unknown                                                                   |
| consolelog_rotate          | Unknown                                                                   |
| contentroot                | Unknown                                                                   |
| coop_fullscreen            | Unknown                                                                   |
| dac_offline                | Unknown                                                                   |
| dedicated                  | Unknown                                                                   |
| dev                        | Enable developer mode                                                     |
| devcontent                 | Unknown                                                                   |
| diff                       | Unknown                                                                   |
| dotatestmodels             | Unknown                                                                   |
| dumpvidmemstats            | Unknown                                                                   |
| dx11                       | Unknown                                                                   |
| dx9                        | Unknown                                                                   |
| dxlevel                    | Unknown                                                                   |
| dxwarp                     | Unknown                                                                   |
| empty                      | Unknown                                                                   |
| enable_2gb_morphs          | Unknown                                                                   |
| error_if_idle              | Unknown                                                                   |
| favor_consistent_framerate | Unknown                                                                   |
| flushlog                   | Unknown                                                                   |
| force_new_recommend        | Unknown                                                                   |
| forcenovsync               | Unknown                                                                   |
| fpexcept                   | Unknown                                                                   |
| framesamples               | Unknown                                                                   |
| fs                         | Unknown                                                                   |
| full_memory_dumps          | Unknown                                                                   |
| full_render_callback_clear | Unknown                                                                   |
| fullscreen                 | Run window fullscreen                                                     |
| game <**path**>            | Path to main game folder                                                  |
| gameinfo_define            | Unknown                                                                   |
| gl                         | Unknown                                                                   |
| gtpoollimitexec            | Unknown                                                                   |
| gtpoolstacksize            | Unknown                                                                   |
| h                          | Unknown                                                                   |
| heapcheck                  | Unknown                                                                   |
| height                     | Unknown                                                                   |
| hideconsole                | Unknown                                                                   |
| high                       | Unknown                                                                   |
| highdpi                    | Unknown                                                                   |
| hushsteam                  | Unknown                                                                   |
| inf                        | Unknown                                                                   |
| insecure                   | Unknown                                                                   |
| ioidlecheck                | Unknown                                                                   |
| language                   | Unknown                                                                   |
| launcherlanguage           | Unknown                                                                   |
| launchersublanguage        | Unknown                                                                   |
| low                        | Unknown                                                                   |
| mainthreadpriority         | Unknown                                                                   |
| mantle                     | Unknown                                                                   |
| msaa                       | Unknown                                                                   |
| multiplier                 | Unknown                                                                   |
| netconpassword             | Unknown                                                                   |
| netconport                 | Unknown                                                                   |
| netspike                   | Unknown                                                                   |
| noPriorityBoost            | Unknown                                                                   |
| no_bundle_module           | Unknown                                                                   |
| no_tier2_bundle            | Unknown                                                                   |
| no_tier3_bundle            | Unknown                                                                   |
| no_vrconfig                | Unknown                                                                   |
| noborder                   | Start the window with no border                                           |
| nobreakpad                 | Unknown                                                                   |
| nodedicatedconsole         | Unknown                                                                   |
| nodev                      | Unknown                                                                   |
| nogamestats                | Unknown                                                                   |
| nohltv                     | Unknown                                                                   |
| nolod                      | Unknown                                                                   |
| nominidumps                | Unknown                                                                   |
| nopanorama                 | Unknown                                                                   |
| nopassiveasserts           | Unknown                                                                   |
| nopvs                      | Unknown                                                                   |
| nosound                    | Unknown                                                                   |
| notoolsdev                 | Unknown                                                                   |
| novconsole                 | Unknown                                                                   |
| novpk                      | Unknown                                                                   |
| novr                       | Disable VR features                                                       |
| novsync                    | Disable vertical sync                                                     |
| nowindow                   | Disable windowed mode                                                     |
| nv                         | Unknown                                                                   |
| pdiff                      | Unknown                                                                   |
| perfectworld               | Unknown                                                                   |
| pme                        | Unknown                                                                   |
| port                       | Unknown                                                                   |
| product                    | Unknown                                                                   |
| profilemapload             | Unknown                                                                   |
| profilemapload_noquit      | Unknown                                                                   |
| publiccontent              | Unknown                                                                   |
| quitonservershutdown       | Unknown                                                                   |
| recordPerfStats            | Unknown                                                                   |
| rendersystemdll            | Unknown                                                                   |
| report                     | Unknown                                                                   |
| reservewarnmb              | Unknown                                                                   |
| resizing                   | Allow the window to be resized                                            |
| rs_reset                   | Unknown                                                                   |
| safe_mode                  | Unknown                                                                   |
| sdl_displayindex           | Unknown                                                                   |
| servertime                 | Unknown                                                                   |
| showasserts                | Unknown                                                                   |
| snap                       | Unknown                                                                   |
| spewserializers            | Unknown                                                                   |
| sse2                       | Unknown                                                                   |
| sse3                       | Unknown                                                                   |
| sse4                       | Unknown                                                                   |
| steam                      | Unknown                                                                   |
| steamhdl_init              | Unknown                                                                   |
| steamlogin_accesscode      | Unknown                                                                   |
| steamlogin_authority       | Unknown                                                                   |
| steamport                  | Unknown                                                                   |
| subprocess                 | Unknown                                                                   |
| sw                         | Start in windowed mode                                                    |
| tempcontent                | Unknown                                                                   |
| textlanguage               | Unknown                                                                   |
| textmessagedebug           | Unknown                                                                   |
| textsublanguage            | Unknown                                                                   |
| threads                    | Unknown                                                                   |
| toconsole                  | Unknown                                                                   |
| tool                       | Unknown                                                                   |
| tools                      | Boot the engine in tools mode                                             |
| toolsonly                  | Unknown                                                                   |
| toolsvr                    | Boot the engine in tools mode **Unsure if this is different from -tools** |
| tvmasteronly               | Unknown                                                                   |
| uidev                      | Unknown                                                                   |
| unbufferedio               | Unknown                                                                   |
| usePriorityBoost           | Unknown                                                                   |
| use_tier2_bundle           | Unknown                                                                   |
| use_tier3_bundle           | Unknown                                                                   |
| useappid                   | Unknown                                                                   |
| uselogdir                  | Unknown                                                                   |
| usercon                    | Unknown                                                                   |
| vconport                   | Unknown                                                                   |
| vconsole                   | Unknown                                                                   |
| vguiconsole                | Unknown                                                                   |
| vguimessages               | Unknown                                                                   |
| vr                         | Enable VR mode                                                            |
| vrdebug                    | Unknown                                                                   |
| vrdemo                     | Unknown                                                                   |
| vsync                      | Enable vertical sync                                                      |
| vulkan                     | Enable Vulkan renderer                                                    |
| w <**int**>                | The width of the window if running in windowed mode                       |
| warmtime                   | Unknown                                                                   |
| width                      | The width of the window if running in windowed mode                       |
| x <**int**>                | The x position of the window if running in windowed mode                  |
| y <**int**>                | The y position of the window if running in windowed mode                  |


## resourcecompiler.dll
> This library is loaded by resourcecompiler.exe while building assets/maps.

| **Flag**                           | **Effect** |
| ---------------------------------- | ---------- |
| width                              | Unknown    |
| w                                  | Unknown    |
| vwatch_locking                     | Unknown    |
| vwatch_disabled                    | Unknown    |
| vwatch                             | Unknown    |
| vulkan                             | Unknown    |
| vsync                              | Unknown    |
| vrdemo                             | Unknown    |
| vrdebug                            | Unknown    |
| vrad3                              | Unknown    |
| vr                                 | Unknown    |
| vpkincr                            | Unknown    |
| vconsole                           | Unknown    |
| vconport                           | Unknown    |
| v                                  | Unknown    |
| usep4port                          | Unknown    |
| useforcedirtyfile                  | Unknown    |
| use_tier3_bundle                   | Unknown    |
| use_tier2_bundle                   | Unknown    |
| unbufferedio                       | Unknown    |
| toolsvr                            | Unknown    |
| tools                              | Unknown    |
| threads                            | Unknown    |
| tempcontent                        | Unknown    |
| sw                                 | Unknown    |
| steam                              | Unknown    |
| staging                            | Unknown    |
| sse4                               | Unknown    |
| sse3                               | Unknown    |
| sse2                               | Unknown    |
| showasserts                        | Unknown    |
| safe_mode                          | Unknown    |
| rs_reset                           | Unknown    |
| rgba                               | Unknown    |
| rgb                                | Unknown    |
| restricted_write_include           | Unknown    |
| resourcecompiler_log_compile_stats | Unknown    |
| resizing                           | Unknown    |
| rendersystemdll                    | Unknown    |
| r                                  | Unknown    |
| publiccontent                      | Unknown    |
| pauseiferror                       | Unknown    |
| pause                              | Unknown    |
| p4cachefiles                       | Unknown    |
| outroot                            | Unknown    |
| nv                                 | Unknown    |
| nowindow                           | Unknown    |
| novwatch                           | Unknown    |
| novsync                            | Unknown    |
| novr                               | Unknown    |
| novpk                              | Unknown    |
| notoolsdev                         | Unknown    |
| normalvis                          | Unknown    |
| norevert                           | Unknown    |
| nop4                               | Unknown    |
| noborder                           | Unknown    |
| noassert                           | Unknown    |
| no_tier3_bundle                    | Unknown    |
| no_tier2_bundle                    | Unknown    |
| no_bundle_module                   | Unknown    |
| msaa                               | Unknown    |
| mobile                             | Unknown    |
| mantle                             | Unknown    |
| logwarnings                        | Unknown    |
| inf                                | Unknown    |
| i                                  | Unknown    |
| html                               | Unknown    |
| highdpi                            | Unknown    |
| help                               | Unknown    |
| height                             | Unknown    |
| h                                  | Unknown    |
| gl                                 | Unknown    |
| gameinfo_define                    | Unknown    |
| game                               | Unknown    |
| fullscreen                         | Unknown    |
| full_memory_dumps                  | Unknown    |
| fshallow2                          | Unknown    |
| fshallow                           | Unknown    |
| fs                                 | Unknown    |
| fpexcept                           | Unknown    |
| forcenovsync                       | Unknown    |
| force_new_recommend                | Unknown    |
| filelist                           | Unknown    |
| fastpack                           | Unknown    |
| f                                  | Unknown    |
| extract_sentence                   | Unknown    |
| enable_2gb_morphs                  | Unknown    |
| empty                              | Unknown    |
| dxwarp                             | Unknown    |
| dxlevel                            | Unknown    |
| dx9                                | Unknown    |
| dx11                               | Unknown    |
| dotatestmodels                     | Unknown    |
| devcontent                         | Unknown    |
| dev                                | Unknown    |
| debug_override_compiler            | Unknown    |
| coop_fullscreen                    | Unknown    |
| contentroot                        | Unknown    |
| consolelog_rotate                  | Unknown    |
| consolelog_notimestamp             | Unknown    |
| consolelog_append                  | Unknown    |
| consolelog                         | Unknown    |
| consoleapp                         | Unknown    |
| conrotate                          | Unknown    |
| condebug                           | Unknown    |
| con_logfile                        | Unknown    |
| changelist                         | Unknown    |
| breakpad                           | Unknown    |
| breakimmediately                   | Unknown    |
| border                             | Unknown    |
| avx                                | Unknown    |
| attachtodebugger                   | Unknown    |
| allowdebug                         | Unknown    |
| allow_non_tools_paths              | Unknown    |
| addon_path                         | Unknown    |
| addon                              | Unknown    |
| adapter                            | Unknown    |
| a                                  | Unknown    |
| 720                                | Unknown    |
| 480                                | Unknown    |
| 1600                               | Unknown    |


## materialsystem2.dll
> This library is loaded by all parts the engine that rely on shaders/rendering. 
> 
> **Examples:** Game window, tools, sfm, things that have a render window
> **Except:** Dedicated server, vpk.exe, command line tools or headless tools

| **Flag**               | **Effect** |
| ---------------------- | ---------- |
| asyncfeatureload       | Unknown    |
| avx                    | Unknown    |
| batchwarnings          | Unknown    |
| cs                     | Unknown    |
| dev                    | Unknown    |
| ds                     | Unknown    |
| gl_use_mobile_vcs      | Unknown    |
| gs                     | Unknown    |
| hs                     | Unknown    |
| inf                    | Unknown    |
| materialsystem2_strict | Unknown    |
| memory                 | Unknown    |
| noasyncmaterialload    | Unknown    |
| noshaderopts           | Unknown    |
| ps                     | Unknown    |
| psrs                   | Unknown    |
| shaderdebugging        | Unknown    |
| shaders                | Unknown    |
| shaderstats            | Unknown    |
| show_none              | Unknown    |
| show_used_combos       | Unknown    |
| sse2                   | Unknown    |
| sse3                   | Unknown    |
| sse4                   | Unknown    |
| vs                     | Unknown    |
| vulkan_use_android_vcs | Unknown    |
| vulkan_use_ios_vcs     | Unknown    |


## rendersystemdx11.dll
> This library is loaded by the engine when the renderer is set to dxlevel 110. Default on Windows.

| **Flag**               | **Effect** |
| ---------------------- | ---------- |
| 4gpu                   | Unknown    |
| adapter                | Unknown    |
| autoconfig             | Unknown    |
| autoconfig_level       | Unknown    |
| avx                    | Unknown    |
| deferTextureLoads      | Unknown    |
| disable_async_shaders  | Unknown    |
| disallowhwmorph        | Unknown    |
| dontEvictTextures      | Unknown    |
| dx11                   | Unknown    |
| dx11debug              | Unknown    |
| dx11debugbreak         | Unknown    |
| dx11renderthreadstack  | Unknown    |
| dx9                    | Unknown    |
| dxwarp                 | Unknown    |
| empty                  | Unknown    |
| force_recommend_gl     | Unknown    |
| forcedx11dx9           | Unknown    |
| gl                     | Unknown    |
| ignoredxsupportcfg     | Unknown    |
| mantle                 | Unknown    |
| maxdxlevel             | Unknown    |
| maxtexturepoolsize_2gb | Unknown    |
| maxtextureres          | Unknown    |
| maxtextureres_2gb      | Unknown    |
| multigpu               | Unknown    |
| noframelatencylimit    | Unknown    |
| nogammaramp            | Unknown    |
| nomipmaps              | Unknown    |
| nomultigpu             | Unknown    |
| oldtexturestreaming    | Unknown    |
| onethreadpool          | Unknown    |
| preloadtextures        | Unknown    |
| r_max_device_threads   | Unknown    |
| sgpu                   | Unknown    |
| shaderstats            | Unknown    |
| shadowTargetSize       | Unknown    |
| sse2                   | Unknown    |
| sse3                   | Unknown    |
| sse4                   | Unknown    |
| suppressdx9            | Unknown    |
| swap_chain_as_is       | Unknown    |
| vulkan                 | Unknown    |


## rendersystemvulkan.dll
> This library is loaded by the engine when the vulkan flag is passed. Default on Linuw.

| **Flag**                                          | **Effect** |
| ------------------------------------------------- | ---------- |
| deferTextureLoads                                 | Unknown    |
| disallowhwmorph                                   | Unknown    |
| disallowhwmorph                                   | Unknown    |
| dontEvictTextures                                 | Unknown    |
| dx11                                              | Unknown    |
| dx11                                              | Unknown    |
| dx9                                               | Unknown    |
| dx9                                               | Unknown    |
| element array of                                  | Unknown    |
| empty                                             | Unknown    |
| end of input-(                                    | Unknown    |
| force_recommend_gl                                | Unknown    |
| gl                                                | Unknown    |
| gl                                                | Unknown    |
| glsl_to_spirv                                     | Unknown    |
| ignoredxsupportcfg                                | Unknown    |
| inf                                               | Unknown    |
| inf                                               | Unknown    |
| lunarg_no_present_fence                           | Unknown    |
| mantle                                            | Unknown    |
| maxdxlevel                                        | Unknown    |
| maxtexturepoolsize_2gb                            | Unknown    |
| maxtextureres                                     | Unknown    |
| maxtextureres_2gb                                 | Unknown    |
| memory-                                           | Unknown    |
| memory-                                           | Unknown    |
| multigpu                                          | Unknown    |
| multigpu                                          | Unknown    |
| newtexturestreaming                               | Unknown    |
| nogammaramp                                       | Unknown    |
| nomultigpu                                        | Unknown    |
| nomultigpu                                        | Unknown    |
| oldtexturestreaming                               | Unknown    |
| preloadtextures                                   | Unknown    |
| r_max_device_threads                              | Unknown    |
| r_max_device_threads                              | Unknown    |
| sgpu                                              | Unknown    |
| sgpu                                              | Unknown    |
| shaderstats                                       | Unknown    |
| shaderstats                                       | Unknown    |
| shadowTargetSize                                  | Unknown    |
| sse2                                              | Unknown    |
| sse3                                              | Unknown    |
| sse4                                              | Unknown    |
| tx-struct                                         | Unknown    |
| unknown source-                                   | Unknown    |
| unknown source-(                                  | Unknown    |
| unknown source-(                                  | Unknown    |
| vulkan                                            | Unknown    |
| vulkan                                            | Unknown    |
| vulkan_aggressive_command_pool_rebalancing        | Unknown    |
| vulkan_aggressive_command_pool_rebalancing_2gb    | Unknown    |
| vulkan_alloc_callbacks                            | Unknown    |
| vulkan_amd_disable_bind_vertex_buffers_workaround | Unknown    |
| vulkan_cmd_buffer_pool_size                       | Unknown    |
| vulkan_depth_texture_as_r32f                      | Unknown    |
| vulkan_descriptor_sets_per_pool                   | Unknown    |
| vulkan_diagnostic_checkpoints                     | Unknown    |
| vulkan_disable_amd_memory_overallocation_behavior | Unknown    |
| vulkan_disable_async_compute                      | Unknown    |
| vulkan_disable_device_coherent_allocations        | Unknown    |
| vulkan_disable_ext_memory_budget                  | Unknown    |
| vulkan_disable_ext_memory_budget                  | Unknown    |
| vulkan_disable_ext_memory_priority                | Unknown    |
| vulkan_disable_ext_separate_stencil_usage         | Unknown    |
| vulkan_disable_ext_validation_cache               | Unknown    |
| vulkan_disable_external_subpass_dependency        | Unknown    |
| vulkan_disable_khr_descriptor_update_template     | Unknown    |
| vulkan_disable_khr_image_format_list              | Unknown    |
| vulkan_disable_khr_maintenance1                   | Unknown    |
| vulkan_disable_khr_maintenance2                   | Unknown    |
| vulkan_disable_khr_swapchain_mutable_format       | Unknown    |
| vulkan_disable_mipgen_compute_shader              | Unknown    |
| vulkan_disable_nv_dedicated_allocation            | Unknown    |
| vulkan_disable_occlusion_queries                  | Unknown    |
| vulkan_disable_occlusion_queries                  | Unknown    |
| vulkan_disable_pipeline_cache                     | Unknown    |
| vulkan_disable_pool_textures                      | Unknown    |
| vulkan_disable_pool_textures                      | Unknown    |
| vulkan_disable_secondary_command_buffers          | Unknown    |
| vulkan_disable_steam_app_shader_cache             | Unknown    |
| vulkan_disable_steam_downloaded_shader_cache      | Unknown    |
| vulkan_disable_steam_shader_cache                 | Unknown    |
| vulkan_disable_swapchain_sampling                 | Unknown    |
| vulkan_disable_validation_api_parameters          | Unknown    |
| vulkan_disable_validation_core_checks             | Unknown    |
| vulkan_disable_validation_object_lifetimes        | Unknown    |
| vulkan_disable_validation_shaders                 | Unknown    |
| vulkan_disable_validation_thread_safety           | Unknown    |
| vulkan_disable_validation_unique_handles          | Unknown    |
| vulkan_dump_shaders                               | Unknown    |
| vulkan_enable_gpu_validation                      | Unknown    |
| vulkan_enable_robust_buffer_access                | Unknown    |
| vulkan_enable_validation                          | Unknown    |
| vulkan_force_sm30                                 | Unknown    |
| vulkan_force_sm30                                 | Unknown    |
| vulkan_metal_validation                           | Unknown    |
| vulkan_minimal_validation                         | Unknown    |
| vulkan_no_image_transitions                       | Unknown    |
| vulkan_scene_system_job_cost                      | Unknown    |
| vulkan_scene_system_job_cost                      | Unknown    |
| vulkan_trim_all_command_pools                     | Unknown    |
| vulkan_trim_all_command_pools_2gb                 | Unknown    |
| vulkan_trim_command_pools                         | Unknown    |
| vulkan_trim_command_pools_2gb                     | Unknown    |
| vulkan_validation_warnings                        | Unknown    |
| vulkan_validation_warnings                        | Unknown    |
| vulkanrenderthreadstack                           | Unknown    |
