JFLAGS = -g
JC = javac
DIR = lox
.SUFFIXES: .java .class
.java.class:
		$(JC) $(JFLAGS) *.java

CLASSES = \
		TokenType.java \
		Token.java \
		Scanner.java \
        Expr.java \
        Parser.java \
        AstPrinter.java \
        Interpreter.java \
		Lox.java 

default: classes

classes: $(CLASSES:.java=.class)

clean:
		$(RM) *.class
