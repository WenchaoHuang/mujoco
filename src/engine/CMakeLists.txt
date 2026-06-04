# Copyright 2021 DeepMind Technologies Limited
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

set(MUJOCO_ENGINE_SRCS
    engine_array_safety.h
    engine_callback.cc
    engine_callback.h
    engine_collision_box.cc
    engine_collision_convex.cc
    engine_collision_convex.h
    engine_collision_driver.cc
    engine_collision_driver.h
    engine_collision_gjk.cc
    engine_collision_gjk.h
    engine_collision_primitive.cc
    engine_collision_primitive.h
    engine_collision_sdf.cc
    engine_collision_sdf.h
    engine_core_constraint.cc
    engine_core_constraint.h
    engine_core_util.cc
    engine_core_util.h
    engine_core_smooth.cc
    engine_core_smooth.h
    engine_crossplatform.cc
    engine_crossplatform.h
    engine_derivative.cc
    engine_derivative.h
    engine_derivative_fd.cc
    engine_derivative_fd.h
    engine_forward.cc
    engine_forward.h
    engine_global_table.h
    engine_inverse.cc
    engine_inverse.h
    engine_init.cc
    engine_init.h
    engine_inline.h
    engine_island.cc
    engine_island.h
    engine_io.cc
    engine_io.h
    engine_macro.h
    engine_memory.cc
    engine_memory.h
    engine_name.cc
    engine_name.h
    engine_passive.cc
    engine_passive.h
    engine_plugin.cc
    engine_plugin.h
    engine_print.cc
    engine_print.h
    engine_ray.cc
    engine_ray.h
    engine_sensor.cc
    engine_sensor.h
    engine_setconst.cc
    engine_setconst.h
    engine_sleep.cc
    engine_sleep.h
    engine_solver.cc
    engine_solver.h
    engine_sort.h
    engine_support.cc
    engine_support.h
    engine_thread.cc
    engine_thread.h
    engine_util_blas.cc
    engine_util_blas.h
    engine_util_blas_avx.h
    engine_util_errmem.cc
    engine_util_errmem.h
    engine_util_misc.cc
    engine_util_misc.h
    engine_util_solve.cc
    engine_util_solve.h
    engine_util_sparse.cc
    engine_util_sparse.h
    engine_util_sparse_avx.h
    engine_util_spatial.cc
    engine_util_spatial.h
    engine_vis_init.cc
    engine_vis_init.h
    engine_vis_interact.cc
    engine_vis_interact.h
    engine_vis_visualize.cc
    engine_vis_visualize.h
)

target_sources(mujoco PRIVATE ${MUJOCO_ENGINE_SRCS})
