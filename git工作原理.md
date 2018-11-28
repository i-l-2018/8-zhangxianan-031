#git工作原理：
=
1.使用git bash here，在这个中输入git clone 仓库网址，就可以吧github仓库中的文件保存到本地。
2.在github中，使用upload files，可以把本地文件上传到github中。
3.当github仓库文件所对应的本地文件发生变化时，本地文件（工作区）右击，选择git GUI here，打开后会自动识别文件中发生的变化，点击使发生变化的文件，使其到达暂存区，然后加上备注点击commit，文件这时到达本地仓库，再点击push，把修改的文件推到远程仓库中。
4.当远程仓库中文件发生变化时，右击本地仓库，打开git GUI here，然后点击remote中的fetch from中的origin，把远程仓库中发生的变动更新到本地仓库中，成功后点击merge中的local merge，点击merge更新到工作区，此过程不需要经过暂存区。
