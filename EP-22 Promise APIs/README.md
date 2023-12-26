Promise.all
wait for all of them to finish
it throw error if any of it fail

Promise.allSettled
diff in case of failure
wait for all promises to settle even after one get fail

Promise.race
who finish first will be winner,irrespective of success/failure
result of first settled promise not array, either err also

Promise.any
wait for first success
if any one get rejected, wait for another success
if all fails give arr(err.errors) of aggregate error
