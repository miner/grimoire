Attempts to coerce its argument into an open java.io.Reader.Default implementations always return a java.io.BufferedReader.Default implementations are provided for Reader, BufferedReader,InputStream, File, URI, URL, Socket, byte arrays, character arrays,and String.If argument is a String, it tries to resolve it first as a URI, thenas a local file name.  URIs with a 'file' protocol are converted tolocal file names.Should be used inside with-open to ensure the Reader is properlyclosed.