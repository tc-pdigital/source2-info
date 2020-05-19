
# Source 2 Command Line Flags Dump

---

**Pull requests welcome!**

Command line flags gleaned by disassembling the following binaries from the Half Life: Alyx Workshop Tools and various other Source 2 tools.

**This list is incomplete and may contain duplicates/missing flags.**

## **Table of Contents**

- [Source 2 Command Line Flags Dump](#source-2-command-line-flags-dump)
  - [**Table of Contents**](#table-of-contents)
  - [**Table Rules**](#table-rules)
  - [**Command line flags (by category)**](#command-line-flags-by-category)
    - [*Developer*](#developer)
    - [*Game*](#game)
    - [*Rendering*](#rendering)
    - [*System*](#system)
    - [*Tools*](#tools)
    - [*Unknown*](#unknown)

## **Table Rules**

Below is an example of the formatting for the command line table

| **Flag**        | **Effect**              | **Category (choose one)**                                                                     | **Status (choose one)**                                                                                          |
| --------------- | ----------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| <**flag_name**> | <**usage_description**> | <br/> `- Developer/Debug` <br/> `- System` <br/> `- Game` <br/> `- Tools` <br/> `- Rendering` | `- Untested` <br/> `- Functional` <br/> `- Non-functional - Valve only` <br/> `- Non-functional - Unknown cause` |

## **Command line flags (by category)**

### *Developer*

| **Flag**                     | **Effect**                                      | **Category**    | **Status**   |
| ---------------------------- | ----------------------------------------------- | --------------- | ------------ |
| **assert**                   | Enable asserts                                  | Developer/Debug | **Untested** |
| **assert_content**           | Unknown                                         | Developer/Debug | **Untested** |
| **assertbreak**              | Unknown                                         | Developer/Debug | **Untested** |
| **break_on_crash**           | Unknown                                         | Developer/Debug | **Untested** |
| **breakimmediately**         | Unknown                                         | Developer/Debug | **Untested** |
| **breakpad**                 | Unknown                                         | Developer/Debug | **Untested** |
| **console**                  | Enable Developer console                        | Developer/Debug | **Untested** |
| **consolelog**               | Unknown                                         | Developer/Debug | **Untested** |
| **consolelog_append**        | Unknown                                         | Developer/Debug | **Untested** |
| **consolelog_notimestamp**   | Unknown                                         | Developer/Debug | **Untested** |
| **consolelog_rotate**        | Unknown                                         | Developer/Debug | **Untested** |
| **debug_exitprocess**        | Unknown                                         | Developer/Debug | **Untested** |
| **debug_override_compiler**  | Unknown                                         | Developer/Debug | **Untested** |
| **debugbreak**               | Unknown                                         | Developer/Debug | **Untested** |
| **dev**                      | Enable developer mode                           | Developer/Debug | **Untested** |
| **devcontent**               | Unknown                                         | Developer/Debug | **Untested** |
| **heapcheck**                | Unknown                                         | Developer/Debug | **Untested** |
| **hideconsole**              | Unknown                                         | Developer/Debug | **Untested** |
| **html**                     | Enable html output to stdout                    | Developer/Debug | **Untested** |
| **logwarnings**              | Unknown                                         | Developer/Debug | **Untested** |
| **memory**                   | Unknown                                         | Developer/Debug | **Untested** |
| **memstackstats_keep_pools** | Unknown                                         | Developer/Debug | **Untested** |
| **minidump_full**            | Unknown                                         | Developer/Debug | **Untested** |
| **minidump_log_path**        | Unknown                                         | Developer/Debug | **Untested** |
| **mobile**                   | Unknown                                         | Developer/Debug | **Untested** |
| **mpi_worker**               | Valve MPI flag, likely not functional in retail | Developer/Debug | **Untested** |
| **no_assert_dialog**         | Disable assert dialogs and force to stdout      | Developer/Debug | **Untested** |
| **no_bundle_module**         | Unknown                                         | Developer/Debug | **Untested** |
| **no_tier2_bundle**          | Unknown                                         | Developer/Debug | **Untested** |
| **no_tier3_bundle**          | Unknown                                         | Developer/Debug | **Untested** |
| **no_vrconfig**              | Unknown                                         | Developer/Debug | **Untested** |
| **noassert**                 | Disable asserts altogether                      | Developer/Debug | **Untested** |
| **nobreakpad**               | Unknown                                         | Developer/Debug | **Untested** |
| **nocustomermachine**        | Unknown                                         | Developer/Debug | **Untested** |
| **nodedicatedconsole**       | Unknown                                         | Developer/Debug | **Untested** |
| **nodev**                    | Unknown                                         | Developer/Debug | **Untested** |
| **nodump**                   | Disable minidumps                               | Developer/Debug | **Untested** |
| **noframelatencylimit**      | Unknown                                         | Developer/Debug | **Untested** |
| **nogamestats**              | Unknown                                         | Developer/Debug | **Untested** |
| **nogammaramp**              | Unknown                                         | Developer/Debug | **Untested** |
| **nohibernate**              | Unknown                                         | Developer/Debug | **Untested** |
| **nohltv**                   | Unknown                                         | Developer/Debug | **Untested** |
| **noloaderlockprobe**        | Unknown                                         | Developer/Debug | **Untested** |
| **nolod**                    | Unknown                                         | Developer/Debug | **Untested** |
| **nominidumps**              | Unknown                                         | Developer/Debug | **Untested** |
| **nomipmaps**                | Unknown                                         | Developer/Debug | **Untested** |
| **nomultigpu**               | Unknown                                         | Developer/Debug | **Untested** |
| **nop4**                     | Unknown                                         | Developer/Debug | **Untested** |
| **nopanorama**               | Unknown                                         | Developer/Debug | **Untested** |
| **nopassiveasserts**         | Unknown                                         | Developer/Debug | **Untested** |
| **noPriorityBoost**          | Unknown                                         | Developer/Debug | **Untested** |
| **NOPROCESSHEAP**            | Unknown                                         | Developer/Debug | **Untested** |
| **nopvs**                    | Unknown                                         | Developer/Debug | **Untested** |
| **norevert**                 | Unknown                                         | Developer/Debug | **Untested** |
| **normalvis**                | Unknown                                         | Developer/Debug | **Untested** |
| **noshaderopts**             | Unknown                                         | Developer/Debug | **Untested** |
| **nosound**                  | Unknown                                         | Developer/Debug | **Untested** |
| **novconsole**               | Unknown                                         | Developer/Debug | **Untested** |
| **novwatch**                 | Unknown                                         | Developer/Debug | **Untested** |
| **p4cachefiles**             | Unknown                                         | Developer/Debug | **Untested** |
| **pauseiferror**             | Unknown                                         | Developer/Debug | **Untested** |
| **preloadtextures**          | Unknown                                         | Developer/Debug | **Untested** |
| **PROCESSHEAP**              | Unknown                                         | Developer/Debug | **Untested** |
| **PROCESSHEAPZEROMEM**       | Unknown                                         | Developer/Debug | **Untested** |
| **profile**                  | Unknown                                         | Developer/Debug | **Untested** |
| **profilemapload**           | Unknown                                         | Developer/Debug | **Untested** |
| **profilemapload_noquit**    | Unknown                                         | Developer/Debug | **Untested** |
| **retail**                   | Unknown                                         | Developer/Debug | **Untested** |
| **safe_mode**                | Unknown                                         | Developer/Debug | **Untested** |
| **show_none**                | Unknown                                         | Developer/Debug | **Untested** |
| **show_used_combos**         | Unknown                                         | Developer/Debug | **Untested** |
| **showasserts**              | Unknown                                         | Developer/Debug | **Untested** |
| **snap**                     | Unknown                                         | Developer/Debug | **Untested** |
| **spewserializers**          | Unknown                                         | Developer/Debug | **Untested** |
| **start_resource_profiling** | Unknown                                         | Developer/Debug | **Untested** |
| **stealthdebugger**          | Unknown                                         | Developer/Debug | **Untested** |
| **textmessagedebug**         | Unknown                                         | Developer/Debug | **Untested** |
| **toconsole**                | Unknown                                         | Developer/Debug | **Untested** |
| **uidev**                    | Unknown                                         | Developer/Debug | **Untested** |
| **usep4port**                | Unknown                                         | Developer/Debug | **Untested** |
| **vconport**                 | Unknown                                         | Developer/Debug | **Untested** |
| **vconsole**                 | Enable VConsole2                                | Developer/Debug | **Untested** |
| **vguiconsole**              | Re-enable legacy VGUI console?                  | Developer/Debug | **Untested** |
| **vguimessages**             | Unknown                                         | Developer/Debug | **Untested** |
| **vrad3**                    | Unknown                                         | Developer/Debug | **Untested** |
| **vrdebug**                  | Unknown                                         | Developer/Debug | **Untested** |
| **vwatch**                   | Unknown                                         | Developer/Debug | **Untested** |
| **vwatch_disabled**          | Unknown                                         | Developer/Debug | **Untested** |
| **vwatch_locking**           | Unknown                                         | Developer/Debug | **Untested** |
| **appidoverride**            | Unknown                                         | Developer/Debug | **Untested** |

### *Game*

| **Flag**                     | **Effect**                       | **Category** | **Status**     |
| ---------------------------- | -------------------------------- | ------------ | -------------- |
| **game**   <*string*>        | Unknown                          | Game         | **Untested**   |
| **gameinfo_define**          | Unknown                          | Game         | **Untested**   |
| **language**   <*string*>    | Unknown                          | Game         | **Untested**   |
| **launcherlanguage**         | Unknown                          | Game         | **Untested**   |
| **launchersublanguage**      | Unknown                          | Game         | **Untested**   |
| **netconpassword**           | Unknown                          | Game         | **Untested**   |
| **netconport**               | Unknown                          | Game         | **Untested**   |
| **netspike**                 | Unknown                          | Game         | **Untested**   |
| **novpk**                    | Unknown                          | Game         | **Untested**   |
| **novr**                     | Disable VR Mode                  | Game         | **Functional** |
| **pause**                    | Unknown                          | Game         | **Untested**   |
| **port**    <*int*>          | Unknown                          | Game         | **Untested**   |
| **textlanguage**             | Unknown                          | Game         | **Untested**   |
| **textsublanguage**          | Unknown                          | Game         | **Untested**   |
| **vrdemo**                   | Leftover from Robot Repair demo? | Game         | **Untested**   |
| **addon**      <*string*>    | Launch game with addon           | Game         | **Untested**   |
| **addon_path**    <*string*> | Addon path                       | Game         | **Untested**   |
| **usercon**                  | Enable RCON remote server admin  | Game         | **Functional** |

### *Rendering*

| **Flag**                                             | **Effect**                                | **Category** | **Status**     |
| ---------------------------------------------------- | ----------------------------------------- | ------------ | -------------- |
| **autoconfig**                                       | Set graphics back to defauls for hardware | Rendering    | **Functional** |
| **autoconfig_level**                                 | Unknown                                   | Rendering    | **Untested**   |
| **border**                                           | Unknown                                   | Rendering    | **Untested**   |
| **dx11**                                             | Enable DX11 rendering API                 | Rendering    | **Functional** |
| **dx11debug**                                        | Unknown                                   | Rendering    | **Untested**   |
| **dx11debugbreak**                                   | Unknown                                   | Rendering    | **Untested**   |
| **dx11renderthreadstack**                            | Unknown                                   | Rendering    | **Untested**   |
| **dx9**                                              | Unknown                                   | Rendering    | **Untested**   |
| **dxlevel**   <*int*>                                | Set Direct X rendering level              | Rendering    | **Functional** |
| **dxwarp**                                           | Unknown                                   | Rendering    | **Untested**   |
| **forcedx11dx9**                                     | Unknown                                   | Rendering    | **Untested**   |
| **fullscreen**                                       | Unknown                                   | Rendering    | **Untested**   |
| **gl**                                               | Unknown                                   | Rendering    | **Untested**   |
| **gl_use_mobile_vcs**                                | Unknown                                   | Rendering    | **Untested**   |
| **glsl_to_spirv**                                    | Unknown                                   | Rendering    | **Untested**   |
| **height**      <*int*>                              | Unknown                                   | Rendering    | **Untested**   |
| **msaa**         <*int*>                             | Enable MSAA anti-aliasing?                | Rendering    | **Untested**   |
| **multigpu**                                         | Unknown                                   | Rendering    | **Untested**   |
| **noborder**                                         | Disable window border                     | Rendering    | **Functional** |
| **novsync**                                          | Prevent Vsync                             | Rendering    | **Functional** |
| **nowindow**                                         | Force game to start fullscreen            | Rendering    | **Functional** |
| **r**                                                | Unknown                                   | Rendering    | **Untested**   |
| **r_max_device_threads**                             | Unknown                                   | Rendering    | **Untested**   |
| **recordPerfStats**                                  | Unknown                                   | Rendering    | **Untested**   |
| **rendersystemdll**                                  | Unknown                                   | Rendering    | **Untested**   |
| **resizing**                                         | Enable window resizing                    | Rendering    | **Functional** |
| **sdl_displayindex**                                 | Unknown                                   | Rendering    | **Untested**   |
| **sgpu**                                             | Unknown                                   | Rendering    | **Untested**   |
| **shaderdebugging**                                  | Unknown                                   | Rendering    | **Untested**   |
| **shaders**                                          | Unknown                                   | Rendering    | **Untested**   |
| **shaderstats**                                      | Unknown                                   | Rendering    | **Untested**   |
| **shadowTargetSize**                                 | Unknown                                   | Rendering    | **Untested**   |
| **sw**                                               | Start in windowed mode                    | Rendering    | **Functional** |
| **swap_chain_as_is**                                 | Unknown                                   | Rendering    | **Untested**   |
| **vs**                                               | Unknown                                   | Rendering    | **Untested**   |
| **vsync**                                            | Enable Vsync                              | Rendering    | **Functional** |
| **vulkan**                                           | Force Vulkan renderer                     | Rendering    | **Untested**   |
| **vulkan_aggressive_command_pool_rebalancing**       | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_aggressive_command_pool_rebalancing_2gb**   | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_alloc_callbacks**                           | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_amd_disable_bind_vertex_buffers_workarou**n | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_cmd_buffer_pool_size**                      | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_depth_texture_as_r32f**                     | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_descriptor_sets_per_pool**                  | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_diagnostic_checkpoints**                    | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_amd_memory_overallocation_behavi**o | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_async_compute**                     | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_device_coherent_allocations**       | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_ext_memory_budget**                 | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_ext_memory_priority**               | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_ext_separate_stencil_usage**        | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_ext_validation_cache**              | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_external_subpass_dependency**       | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_khr_descriptor_update_template**    | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_khr_image_format_list**             | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_khr_maintenance1**                  | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_khr_maintenance2**                  | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_khr_swapchain_mutable_format**      | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_mipgen_compute_shader**             | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_nv_dedicated_allocation**           | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_occlusion_queries**                 | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_pipeline_cache**                    | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_pool_textures**                     | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_secondary_command_buffers**         | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_steam_app_shader_cache**            | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_steam_downloaded_shader_cache**     | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_steam_shader_cache**                | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_swapchain_sampling**                | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_validation_api_parameters**         | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_validation_core_checks**            | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_validation_object_lifetimes**       | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_validation_shaders**                | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_validation_thread_safety**          | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_disable_validation_unique_handles**         | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_dump_shaders**                              | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_enable_gpu_validation**                     | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_enable_robust_buffer_access**               | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_enable_validation**                         | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_force_sm30**                                | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_metal_validation**                          | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_minimal_validation**                        | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_no_image_transitions**                      | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_scene_system_job_cost**                     | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_trim_all_command_pools**                    | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_trim_all_command_pools_2gb**                | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_trim_command_pools**                        | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_trim_command_pools_2gb**                    | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_use_android_vcs**                           | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_use_ios_vcs**                               | Unknown                                   | Rendering    | **Untested**   |
| **vulkan_validation_warnings**                       | Unknown                                   | Rendering    | **Untested**   |
| **vulkanrenderthreadstack**                          | Unknown                                   | Rendering    | **Untested**   |
| **w**        <*int*>                                 | Set window width                          | Rendering    | **Untested**   |
| **width**       <*int*>                              | Set window width                          | Rendering    | **Untested**   |
| **x**           <*int*>                              | Set window X position                     | Rendering    | **Untested**   |
| **y**             <*int*>                            | Set window Y position                     | Rendering    | **Untested**   |
| **1600**                                             | Set render width to 1600                  | Rendering    | **Untested**   |
| **480**                                              | Set render height to 480                  | Rendering    | **Untested**   |
| **4gpu**                                             | Enable Multi-GPU?                         | Rendering    | **Untested**   |
| **720**                                              | Set render height to 720                  | Rendering    | **Untested**   |
| **adapter**                                          | Unknown                                   | Rendering    | **Untested**   |
| **forcenovsync**                                     | Disable VSync                             | Rendering    | **Functional** |

### *System*

| **Flag**                  | **Effect**                                                    | **Category** | **Status**     |
| ------------------------- | ------------------------------------------------------------- | ------------ | -------------- |
| **allowmultiple**         | Allow multiple instances of the engine?                       | System       | **Untested**   |
| **allthreads**            | Unknown                                                       | System       | **Untested**   |
| **fs**                    | Unknown                                                       | System       | **Untested**   |
| **high**                  | Unknown                                                       | System       | **Untested**   |
| **highdpi**               | Unknown                                                       | System       | **Untested**   |
| **hushsteam**             | Unknown                                                       | System       | **Untested**   |
| **insecure**              | Unknown                                                       | System       | **Untested**   |
| **low**                   | Unknown                                                       | System       | **Untested**   |
| **sse2**                  | Enable SSE2 CPU features?                                     | System       | **Untested**   |
| **sse3**                  | Enable SSE3 CPU features?                                     | System       | **Untested**   |
| **sse4**                  | Enable SSE4 CPU features?                                     | System       | **Untested**   |
| **staging**               | Unknown                                                       | System       | **Untested**   |
| **steam**                 | Start with Steam integration, this is forced on retail builds | System       | **Functional** |
| **steamhdl_init**         | Unknown                                                       | System       | **Untested**   |
| **steamlogin_accesscode** | Unknown                                                       | System       | **Untested**   |
| **steamlogin_authority**  | Unknown                                                       | System       | **Untested**   |
| **steamport**             | Unknown                                                       | System       | **Untested**   |
| **subprocess**            | Unknown                                                       | System       | **Untested**   |
| **suppressdx9**           | Unknown                                                       | System       | **Untested**   |
| **threads**               | Set max number of CPU threads?                                | System       | **Untested**   |
| **useappid**              | Unknown                                                       | System       | **Untested**   |
| **usePriorityBoost**      | Unknown                                                       | System       | **Untested**   |
| **vr**                    | Enable VR mode                                                | System       | **Functional** |
| **2GB**                   | Unknown                                                       | System       | **Untested**   |
| **dedicated**             | Start dedicated server                                        | System       | **Functional** |
| **help**                  | Print usage                                                   | System       | **Functional** |

### *Tools*

| **Flag**          | **Effect**                       | **Category** | **Status**     |
| ----------------- | -------------------------------- | ------------ | -------------- |
| **notoolsdev**    | Unknown                          | Tools        | **Untested**   |
| **tool**          | Select startup tool?             | Tools        | **Untested**   |
| **tools**         | Start in tools mode              | Tools        | **Functional** |
| **toolsonly**     | Start only tools and not engine? | Tools        | **Untested**   |
| **toolsvr**       | Enable VR mode in tools?         | Tools        | **Untested**   |
| **buildcubemaps** | Build cubemaps on load           | Tools        | **Functional** |

### *Unknown*

| **Flag**                               | **Effect**                | **Category** | **Status**   |
| -------------------------------------- | ------------------------- | ------------ | ------------ |
| **a**                                  | Unknown                   | Unknown      | **Untested** |
| **allocwarnmb**                        | Unknown                   | Unknown      | **Untested** |
| **allow_no_lobby_connect**             | Unknown                   | Unknown      | **Untested** |
| **allow_non_tools_paths**              | Unknown                   | Unknown      | **Untested** |
| **allowdebug**                         | Unknown                   | Unknown      | **Untested** |
| **asset**                              | Unknown                   | Unknown      | **Untested** |
| **asyncfeatureload**                   | Unknown                   | Unknown      | **Untested** |
| **attachtodebugger**                   | Unknown                   | Unknown      | **Untested** |
| **avx**                                | Unknown                   | Unknown      | **Untested** |
| **background**                         | Start game in background? | Unknown      | **Untested** |
| **batchwarnings**                      | Unknown                   | Unknown      | **Untested** |
| **bench**                              | Benchmark tool?           | Unknown      | **Untested** |
| **benchframes**                        | Unknown                   | Unknown      | **Untested** |
| **benchnoexit**                        | Unknown                   | Unknown      | **Untested** |
| **benchnote**                          | Unknown                   | Unknown      | **Untested** |
| **benchtime**                          | Unknown                   | Unknown      | **Untested** |
| **bugvoice**                           | Unknown                   | Unknown      | **Untested** |
| **c**                                  | Unknown                   | Unknown      | **Untested** |
| **changelist**                         | Unknown                   | Unknown      | **Untested** |
| **clearassertstate**                   | Unknown                   | Unknown      | **Untested** |
| **clientonly**                         | Unknown                   | Unknown      | **Untested** |
| **comment**                            | Unknown                   | Unknown      | **Untested** |
| **component**                          | Unknown                   | Unknown      | **Untested** |
| **con_logfile**                        | Unknown                   | Unknown      | **Untested** |
| **condebug**                           | Unknown                   | Unknown      | **Untested** |
| **conrotate**                          | Unknown                   | Unknown      | **Untested** |
| **consoleapp**                         | Unknown                   | Unknown      | **Untested** |
| **contentroot**   <*string*>           | Unknown                   | Unknown      | **Untested** |
| **coop_fullscreen**                    | Unknown                   | Unknown      | **Untested** |
| **cs**                                 | Unknown                   | Unknown      | **Untested** |
| **dac_offline**                        | Unknown                   | Unknown      | **Untested** |
| **deferTextureLoads**                  | Unknown                   | Unknown      | **Untested** |
| **diff**                               | Unknown                   | Unknown      | **Untested** |
| **disable_affinity_preference**        | Unknown                   | Unknown      | **Untested** |
| **disable_async_shaders**              | Unknown                   | Unknown      | **Untested** |
| **disable_minidump_log**               | Unknown                   | Unknown      | **Untested** |
| **disablehangwatchdog**                | Unknown                   | Unknown      | **Untested** |
| **disallowhwmorph**                    | Unknown                   | Unknown      | **Untested** |
| **dontEvictTextures**                  | Unknown                   | Unknown      | **Untested** |
| **dotatestmodels**                     | Unknown                   | Unknown      | **Untested** |
| **ds**                                 | Unknown                   | Unknown      | **Untested** |
| **dumpvidmemstats**                    | Unknown                   | Unknown      | **Untested** |
| **element array of**                   | Unknown                   | Unknown      | **Untested** |
| **emaildumps**                         | Unknown                   | Unknown      | **Untested** |
| **empty**                              | Unknown                   | Unknown      | **Untested** |
| **enable_2gb_morphs**                  | Unknown                   | Unknown      | **Untested** |
| **enable_minidump_log**                | Unknown                   | Unknown      | **Untested** |
| **entrypoint**                         | Unknown                   | Unknown      | **Untested** |
| **error**                              | Unknown                   | Unknown      | **Untested** |
| **error_if_idle**                      | Unknown                   | Unknown      | **Untested** |
| **etwprofile**                         | Unknown                   | Unknown      | **Untested** |
| **extract_sentence**                   | Unknown                   | Unknown      | **Untested** |
| **f**                                  | Unknown                   | Unknown      | **Untested** |
| **fastpack**                           | Unknown                   | Unknown      | **Untested** |
| **favor_consistent_framerate**         | Unknown                   | Unknown      | **Untested** |
| **filelist**                           | Unknown                   | Unknown      | **Untested** |
| **flushlog**                           | Unknown                   | Unknown      | **Untested** |
| **force_assert_sdl_dialog**            | Unknown                   | Unknown      | **Untested** |
| **force_battery_level**                | Unknown                   | Unknown      | **Untested** |
| **force_battery_level_battery**        | Unknown                   | Unknown      | **Untested** |
| **force_dpi**                          | Unknown                   | Unknown      | **Untested** |
| **force_new_recommend**                | Unknown                   | Unknown      | **Untested** |
| **force_recommend_gl**                 | Unknown                   | Unknown      | **Untested** |
| **fpexcept**                           | Unknown                   | Unknown      | **Untested** |
| **framesamples**                       | Unknown                   | Unknown      | **Untested** |
| **fshallow**                           | Unknown                   | Unknown      | **Untested** |
| **fshallow2**                          | Unknown                   | Unknown      | **Untested** |
| **full_memory_dumps**                  | Unknown                   | Unknown      | **Untested** |
| **full_render_callback_clear**         | Unknown                   | Unknown      | **Untested** |
| **gs**                                 | Unknown                   | Unknown      | **Untested** |
| **gtpoollimitexec**                    | Unknown                   | Unknown      | **Untested** |
| **gtpoolstacksize**                    | Unknown                   | Unknown      | **Untested** |
| **h**                                  | Unknown                   | Unknown      | **Untested** |
| **hs**                                 | Unknown                   | Unknown      | **Untested** |
| **i**                                  | Unknown                   | Unknown      | **Untested** |
| **ignorecontentasserts**               | Unknown                   | Unknown      | **Untested** |
| **ignoredxsupportcfg**                 | Unknown                   | Unknown      | **Untested** |
| **indir**                              | Unknown                   | Unknown      | **Untested** |
| **inf**                                | Unknown                   | Unknown      | **Untested** |
| **inset_bottom**                       | Unknown                   | Unknown      | **Untested** |
| **inset_left**                         | Unknown                   | Unknown      | **Untested** |
| **inset_right**                        | Unknown                   | Unknown      | **Untested** |
| **inset_top**                          | Unknown                   | Unknown      | **Untested** |
| **ioidlecheck**                        | Unknown                   | Unknown      | **Untested** |
| **lunarg_no_present_fence**            | Unknown                   | Unknown      | **Untested** |
| **mainthreadpriority**                 | Unknown                   | Unknown      | **Untested** |
| **mantle**                             | Unknown                   | Unknown      | **Untested** |
| **materialsystem2_strict**             | Unknown                   | Unknown      | **Untested** |
| **maxdxlevel**                         | Unknown                   | Unknown      | **Untested** |
| **maxtexturepoolsize_2gb**             | Unknown                   | Unknown      | **Untested** |
| **maxtextureres**                      | Unknown                   | Unknown      | **Untested** |
| **maxtextureres_2gb**                  | Unknown                   | Unknown      | **Untested** |
| **multiplier**                         | Unknown                   | Unknown      | **Untested** |
| **newtexturestreaming**                | Unknown                   | Unknown      | **Untested** |
| **noasyncmaterialload**                | Unknown                   | Unknown      | **Untested** |
| **noautoargs**                         | Unknown                   | Unknown      | **Untested** |
| **nv**                                 | Unknown                   | Unknown      | **Untested** |
| **oldtexturestreaming**                | Unknown                   | Unknown      | **Untested** |
| **onethreadpool**                      | Unknown                   | Unknown      | **Untested** |
| **outdir**                             | Unknown                   | Unknown      | **Untested** |
| **outroot**                            | Unknown                   | Unknown      | **Untested** |
| **pdiff**                              | Unknown                   | Unknown      | **Untested** |
| **perfectworld**                       | Unknown                   | Unknown      | **Untested** |
| **phased_window_create**               | Unknown                   | Unknown      | **Untested** |
| **pme**                                | Unknown                   | Unknown      | **Untested** |
| **product**                            | Unknown                   | Unknown      | **Untested** |
| **ps**                                 | Unknown                   | Unknown      | **Untested** |
| **psrs**                               | Unknown                   | Unknown      | **Untested** |
| **publiccontent**                      | Unknown                   | Unknown      | **Untested** |
| **quitonservershutdown**               | Unknown                   | Unknown      | **Untested** |
| **report**                             | Unknown                   | Unknown      | **Untested** |
| **RESERVELOWMEM**                      | Unknown                   | Unknown      | **Untested** |
| **reservewarnmb**                      | Unknown                   | Unknown      | **Untested** |
| **resourcecompiler_log_compile_stats** | Unknown                   | Unknown      | **Untested** |
| **restricted_write_include**           | Unknown                   | Unknown      | **Untested** |
| **rgb**                                | Unknown                   | Unknown      | **Untested** |
| **rgba**                               | Unknown                   | Unknown      | **Untested** |
| **rs_reset**                           | Unknown                   | Unknown      | **Untested** |
| **script**      <*int*>                | Unknown                   | Unknown      | **Untested** |
| **servertime**                         | Unknown                   | Unknown      | **Untested** |
| **tempcontent**                        | Unknown                   | Unknown      | **Untested** |
| **testmode**                           | Unknown                   | Unknown      | **Untested** |
| **tvmasteronly**                       | Unknown                   | Unknown      | **Untested** |
| **tx-struct**                          | Unknown                   | Unknown      | **Untested** |
| **unbufferedio**                       | Unknown                   | Unknown      | **Untested** |
| **use_tier2_bundle**                   | Unknown                   | Unknown      | **Untested** |
| **use_tier3_bundle**                   | Unknown                   | Unknown      | **Untested** |
| **useforcedirtyfile**                  | Unknown                   | Unknown      | **Untested** |
| **uselogdir**                          | Unknown                   | Unknown      | **Untested** |
| **v**                                  | Unknown                   | Unknown      | **Untested** |
| **vminidump_exception_code**           | Unknown                   | Unknown      | **Untested** |
| **vpkincr**                            | Unknown                   | Unknown      | **Untested** |
| **warmtime**                           | Unknown                   | Unknown      | **Untested** |
