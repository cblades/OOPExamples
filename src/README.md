# Typical Project Structure
You can make just about any directory strucutre work for you, but typically, a project will have a top level directory (`OOPExamples/`, for this one) that will have build files, a README, a license file, and other non-code things.

Typically, you'll find the 'good stuff' in `src/`, meaning sourcecode and resources.  You may see `src/main/` and `src/test/`.  `src/main/java/` will contain 'live' java sourcecode, and `src/test/` will contain code and utilities meant to validate that the code in `src/main/` works as expected.

It is unusual for there to be files directly in `src/`.

## Who Cares?!
If your project has a handful of sourcecode files, it might seem like the a ton of boilerplate to create the `project/src/main/java/` directory structure; however, if your project has several hundred files, it is way easier for people to navigate if it conforms to an expected structure.