cmake_minimum_required(VERSION {{cookiecutter.cmake_min_ver}} FATAL_ERROR)

project({{cookiecutter.project_slug}} VERSION {{cookiecutter.project_major_version}}.{{cookiecutter.project_minor_version}}.{{cookiecutter.project_patch_version}} LANGUAGES {{cookiecutter.language}})

add_subdirectory(${PROJECT_SOURCE_DIR}/${PROJECT_NAME})