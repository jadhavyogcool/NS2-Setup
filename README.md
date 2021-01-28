#Download the files from the drive link
https://drive.google.com/file/d/1sMfJhK9MxoxgYeq9GIu_Q6Du_a--VikT/view

#Before cloning the repo make sure the below check is done

Just make sure, Your windows defender is turned off as shown below.

![Screenshot (615)](https://user-images.githubusercontent.com/61947484/105715445-a1fb9880-5f43-11eb-9ceb-ee58b3c53b3a.png)

# Steps To Install the Cgywin and NS2 
1) First clone the repository using 
```
git clone clone-path
```
2) After cloning the repository, Extract the files of NS 2.35.part1.rar files.
The following image is the screenshot after extracting the file
![Screenshot (597)](https://user-images.githubusercontent.com/61947484/105708866-00704900-5f3b-11eb-9973-d0b47f906f8a.png)

3) Inside NS2.35 you need to extract ns-allinone-2.35-RC7avecxgraph.rar file. Then after exteacting the file, we can see ns-allinone 2.35-RC7

![Screenshot (610)](https://user-images.githubusercontent.com/61947484/105713460-344e6d00-5f41-11eb-9b8c-1e907bb103d4.png)


4) Now double click on the "setup.exe" to install cgwin. You can see a pop window appearing for setup of cgywin.

![Screenshot (598)](https://user-images.githubusercontent.com/61947484/105709719-1a5e5b80-5f3c-11eb-9e1a-277286759015.png)
Just click on next 

5) Click on option download from the local directory
![Screenshot (602)](https://user-images.githubusercontent.com/61947484/105710037-9062c280-5f3c-11eb-866f-6a48ce47caff.png)
And click on next,  after that.

6) Dont change the root directory keep it as an same root directory,

```
c:\cygwin
```
![Screenshot (603)](https://user-images.githubusercontent.com/61947484/105710275-e172b680-5f3c-11eb-99b9-c48e85d9ced5.png)

7) Now this is an very important step, were you need to change the "Local package directory".
![Screenshot (605)](https://user-images.githubusercontent.com/61947484/105711192-395ded00-5f3e-11eb-87a6-c51cc20cd0f2.png)

click on browse and change the directory to: \NS2 details\My 4shared\NS 2.35\nslocal\http%3a%2f%2fcygwinmirror.3gforphones.com%2f\release\

![Screenshot (604)](https://user-images.githubusercontent.com/61947484/105711464-98236680-5f3e-11eb-800d-165e0ea5fc84.png)
After browsing the directory, just click on "ok" button. 

8) The option will have default, we need to make to install option by just clciking on the default it will show install.
![Screenshot (606)](https://user-images.githubusercontent.com/61947484/105711733-f6504980-5f3e-11eb-9613-f2f103d7a7ed.png)

9) Now wait for some time, cgwin will be installing in your desktop. After installing you can see a icon, in the desktop. After installing in cgwin successfully,just double click on the cgwin you can see cmd of cgwin gets opned, its because it need to intialize all its paths.

![Screenshot (607)](https://user-images.githubusercontent.com/61947484/105712775-4b408f80-5f40-11eb-809f-78b79cc7e689.png)

10) Make a new folder, named "Noureddine", inside home of cgwin.
![Screenshot (608)](https://user-images.githubusercontent.com/61947484/105713165-cc982200-5f40-11eb-8808-d5a7ae428e5a.png)

11) Copy the ".sourcehrc" file from the your ns2.35 partone and pace it inside the "home\user new\" folder of cgwin.

![Screenshot (611)](https://user-images.githubusercontent.com/61947484/105714100-f30a8d00-5f41-11eb-9e83-85b8eedbb5a7.png)

12) Place the extracted, file inside the Noureedine folder.

![Screenshot (609)](https://user-images.githubusercontent.com/61947484/105713270-f05b6800-5f40-11eb-9379-1c64cdce94a2.png)

13) Now try to extract the examples folder which is provided in the github, inside:
```
C:\cygwin\home\Noureddine\ns-allinone-2.35-RC7\ns-2.35\tcl\ex
```

14) After extracting, files over there try keep your nam.exe file in the 
```
C:\cygwin\home\Noureddine\ns-allinone-2.35-RC7\ns-2.35\tcl\ex\examples
```
as shown in the screenshot, to run the output file.
![Screenshot (612)](https://user-images.githubusercontent.com/61947484/105714879-eb97b380-5f42-11eb-86b2-263a36006d3d.png)

Now you are good to go, you installation is done. You can double click on the nam.exe and select the output file to run.
![Screenshot (613)](https://user-images.githubusercontent.com/61947484/105715138-3c0f1100-5f43-11eb-9bdd-d247af487fe7.png)

![Screenshot (614)](https://user-images.githubusercontent.com/61947484/105715285-6cef4600-5f43-11eb-9112-6caafd05d372.png)