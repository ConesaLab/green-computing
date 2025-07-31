1. Understand the benefits of green computing to the new incorporations: green computing is not just a way of working with the environment in mind, but also has intrinsic benefits for the team and the group. Explaining these concepts is the first step towards a full understanding of a group of practices.

2. Turn off your local computer when done. While most of the time we work with remote servers or HPCs, Desktop PCs are a non-stop source of energy consumption. While maybe it's a much lesser consumption than a non-stop HPC analyzing several samples at once, it also contributes to the daily maintenance of hardware. Over time, several computers on for hours without use can contribute to a similar degree than scientific computation attempts.

3. Use local first, then on-site infrastructure, then cloud: Cloud services are very useful because they provide an infinite amount of services. However, sending huge amounts of data over the internet to a server somewhere in the world takes not only time but also energy. On-site infrastructure, on the other hand, usually has mechanisms to transfer data from drives directly to the desired folder. However, none of this matters if the problem is small enough to fit in a regular PC in a reasonable amount of time.

4. When using cloud computing, choose cloud services powered by renewable energies. https://www.ismsforum.es/ficheros/descargas/estudio-green-cloud1663784543.pdf

5. Avoid unnecessary execution: Sometimes, when programming or analyzing a dataset, we tend to test the integration of whole modules or all steps of a pipeline whenever we want. It’s easy to see why this is a bad idea when pipelines take a long time to execute, but when it’s a matter of seconds, people tend to re-run short iterations that, together, waste a considerable amount of time. 

6. Make programs have checkpoints where they can be restarted. Necessary executions should be run with only the necessary steps. If preprocessing is done, and has not changed, it will generate the same output, thus consuming resources that could be saved or used efficiently.

7. Use workflow management systems whenever possible. Workflow management systems, such as nextflow, have interesting features that can avoid unnecessary running time wasted. They are more than just community-accepted standard protocols, as they provide several tools

8. Incorporations are encouraged to benchmark the tools they make or to use the pipelines according to the recommended instructions with the aim of accelerating the computations. Tools that are more efficient are preferred to tools less efficient, as long as the solution they provide is correct. Tools like green algorithms are encouraged to use when needed

9. New incorporations are taught how to check the efficiency of the executed pipelines using Garnatxa HPC tools available to any user, via the SLURM commands. The goal is to understand why they have asked for unneeded resources or the system took non-optimal time to compute.

10. Minimize printing as much as possible, and keep email concise and in digital format.
