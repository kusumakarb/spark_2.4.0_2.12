# spark_2.4.0_2.12
Spark 2.4.0 artifacts compiled with scala 2.12

[Building Spark](https://github.com/apache/spark/blob/master/docs/building-spark.md)

```./dev/change-scala-version.sh 2.12```

```./build/mvn -DskipTests -Pscala-2.12 clean package```

