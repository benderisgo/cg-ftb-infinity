# FTB Infinity

For instructions on how to use this docker image, see [dlord/minecraft][].

## Pull Request Guidelines

All pull requests must have a description, and commit messages must follow
the Linux Kernel standards. Please see [Care And Operation Of Your Linus Torvalds][]
or [How to Write a Git Commit Message][] by Chris Beams.


[Care And Operation Of Your Linus Torvalds]: https://www.kernel.org/doc/Documentation/SubmittingPatches
[How to Write a Git Commit Message]: http://chris.beams.io/posts/git-commit/

[dlord/minecraft]: https://hub.docker.com/r/dlord/minecraft/


docker run \
    --name cg_poz_01 \
    -p 0.0.0.0:25565:25565 \
    -d \
	-t \
    -e DEFAULT_OP=xBendingUnit22x \
    -e MINECRAFT_EULA=true \
    cg_poz2
	
docker run \
    --name cg_poz_02 \
    -p 0.0.0.0:25575:25575 \
    -d \
	-t \
    -e DEFAULT_OP=xBendingUnit22x \
    -e MINECRAFT_EULA=true \
	-e LEVEL_NAME=squanch	\
    cg_poz3