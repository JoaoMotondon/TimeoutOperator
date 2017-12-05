# TimeoutOperator
This project is the sixth part of a series of 10 articles about RxJava operators. It contains some examples of the timeout operator that is  used to issue an error or fallback to another Observable in case of a period of time elapses without any emitted items from the source. RxJava provides several variants of it.

Here is a list of all examples available in this project:

  - timeout(w/duration)
  - timeout(w/second Observable)
  - timeout(w/function)
  - timeout(w/function and a second Observable)
  - timeout(...) putting all together
  - bonus example (that shows timeout and retryWhen together)

Please, refer to [this article](http://androidahead.com/2017/12/05/rxjava-operators-part-6-timeout-operator/) for detailed information.

![Demo](https://user-images.githubusercontent.com/4574670/33601398-3b6a9b04-d993-11e7-990e-43d15bdbfa98.gif)

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
