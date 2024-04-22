# MultipleDynamicModuleCase
Showing dynamic modules cannot share dependencies
main branch issue -
Execution failed for task ':app:checkReleaseLibraries'.

[:dynamicfeature1, :dynamicfeature2] all package the same library [com.jakewharton.timber:timber;Capability: group='com.jakewharton.timber', name='timber'].


Base lib issue -
Execution failed for task ':app:checkReleaseLibraries'.
> [:dynamicfeature1, :dynamicfeature2] all package the same library [:timberlib;Capability: group='MultipleDynamicModuleCase', name='timberlib'].
  [:dynamicfeature1, :dynamicfeature2] all package the same library [com.jakewharton.timber:timber;Capability: group='com.jakewharton.timber', name='timber'].
