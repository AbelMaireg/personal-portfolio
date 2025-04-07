<template>
  <Card>
    <CardHeader>
      <CardTitle><h1>Abel Maireg</h1></CardTitle>
      <CardDescription>Software Engineer</CardDescription>
    </CardHeader>
    <CardContent>
      <div class="content-wrapper flex flex-row-reverse gap-12 p-3">
        <p class="description text-justify">
          I am a software engineer with a passion for building web applications.
          I have experience in various programming languages and frameworks, and
          I enjoy learning new technologies. In my free time, I like to
          contribute to open-source projects and work on personal projects that
          challenge my skills. I am always looking for opportunities to grow and
          improve as a developer. I believe in the power of collaboration and
          teamwork, and I enjoy working with others to create innovative
          solutions. If you are interested in collaborating or have any
          questions, feel free to reach out!
        </p>
      </div>
    </CardContent>
    <CardFooter>
      <DeveloperWebLinks />
    </CardFooter>
  </Card>
</template>

<style scoped>
.content-wrapper {
  flex: 1 1 0%;
}
.description {
  flex: 1;
}
</style>
