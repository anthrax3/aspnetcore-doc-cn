

Enumerator Struct
=================



.. contents:: 
   :local:













Syntax
------

.. code-block:: csharp

   public struct Enumerator : IEnumerator<KeyValuePair<string, StringValues>>, IDisposable, IEnumerator





GitHub
------

`View on GitHub <https://github.com/aspnet/kestrelhttpserver/blob/master/src/Microsoft.AspNet.Server.Kestrel/Http/FrameResponseHeaders.cs>`_





.. dn:structure:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator

Methods
-------

.. dn:structure:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator.Dispose()
    
        
    
        
        .. code-block:: csharp
    
           public void Dispose()
    
    .. dn:method:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator.MoveNext()
    
        
        :rtype: System.Boolean
    
        
        .. code-block:: csharp
    
           public bool MoveNext()
    
    .. dn:method:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator.Reset()
    
        
    
        
        .. code-block:: csharp
    
           public void Reset()
    

Properties
----------

.. dn:structure:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator
    :noindex:
    :hidden:

    
    .. dn:property:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator.Current
    
        
        :rtype: System.Collections.Generic.KeyValuePair{System.String,Microsoft.Extensions.Primitives.StringValues}
    
        
        .. code-block:: csharp
    
           public KeyValuePair<string, StringValues> Current { get; }
    
    .. dn:property:: Microsoft.AspNet.Server.Kestrel.Http.FrameResponseHeaders.Enumerator.System.Collections.IEnumerator.Current
    
        
        :rtype: System.Object
    
        
        .. code-block:: csharp
    
           object IEnumerator.Current { get; }
    

