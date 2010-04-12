# RubyKaigi 2009: Ruby C10K challenge - High Performance Networking (case study with EM-Proxy)

Ruby is often described as a DSL for web services and the popularity of frameworks such as Rails and Merb is a clear sign of success of the language. However, there is also the ongoing concern of scalability and performance of Ruby based web applications. In this talk we will investigate the challenges and dispel the myths around the Ruby networking stack:

- Working with Ruby sockets
- Synchronous and asynchronous polling techniques
- Reactor loop pattern in Ruby (EventMachine)
- Ruby C10K challenge: working with epoll, kqueue, and others

During the presentation we will walk through hands on examples of each of these patterns and learn about the available architectures and libraries for building high-performance network applications in Ruby. As it turns out, it is not impossible to handle 10,000 client connections in Ruby, come out and learn how!

Online slides:

- http://www.slideshare.net/igrigorik/ruby-c10k-high-performance-networking-rubykaigi-09

Contact:

- Blog: www.igvita.com
- Twitter: www.twitter.com/igrigorik